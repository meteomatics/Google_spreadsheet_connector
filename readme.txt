1. Open the Meteomatics Weather API spreadsheet in Excel
2. Go to Google drive
3. Create blank new Google spreadsheet.
4. Copy & Paste the Excel's spreadsheet content to the Google spreadsheet

5. Go to Menu Extensions -> App scripts
6. Remove the entire function "myfunction" that was automatically created.
7. Copy & Paste the WeatherAPI.txt content into that script.

8. Execute the function "onOpen" in the Script Editor. This is needed only once and creates the menu 
entry that you will see in the main menu above the Google spreadsheet.
To do so choose on top next to the Debug icon onOpen function in a dropdown menu. Click the Run.
Execution should be started and then completed. 
9. Google might ask you to grant the script the necessary permissions. That requires logging in to your google account (after clicking on Review permissions) and Allowing the action after logging in. 
10. Go to the Google spreadsheet and execute the new menu entry "Call weather API -> Query API"
11. The spreadsheet should be updated a few seconds later.

FAQ: Depending on your license it might be that you can not query data older than 2 days.
Change the dates based on the license as the error message might suggest. For example, it might happen that the date to query is too old and not supported for the license, just change the dates to a newer ones. 