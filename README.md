# webSraping
scrape the web the type result in xl sheet
In the RPA Studio:
⦁	Create a PROJECT to do the following:
- Open a dialog with the user to accept a STRING value, prompting the user to enter their name and the current date
- write this dialogue result to the Output panel in the tool 
 
- open a NEW Notepad file
- write the same text in an Notepad file and save it titled : <Last Name - First Name> - RPA_09.txt (substitute your last name and first name value) [5 points]
 
ATTACH a new Document instance to the Project
- Open each provided Source Data File
- Extract  the tabular data (NOT including the header record) and append it to any existing data in the Excel template - Tab "Production LIst" - Columns A through G
DO NOT disrupt the calculations in columns H and I
Extra Reference Source for Word Data Table Capture (Links to an external site.) 
[5 points]
 
- Write message to the Notepad file indicating which data file provided the source [5 points]
 
- Output the data file name and timestamp to the Output panel [5 points]
 
⦁	Open the provided EXCEL Template
- Open each provided Document (in any sequence)
- Append the formatted data from the body of the Word table (DO NOT include the Header row) into the main Workbook formatted table (see instruction above)
- When all Word file contents are in the main Workbook table - confirm that the calculated columns H and I contain values (NOTE: The calculation is provided as a text value in the first row of the workbook as a reference in case you need to reinstate it)
- REFRESH the Pivot Tables from the updated master table
- FILTER the Pivot Table on the Manager Approvals tab by ONE Manager at a time [5 points - visible in the email content]
 
⦁	 Create the EMAIL
- Create a NEW Email for each MANAGER [Edmilson, Homero, Marin]  with the list of modules included in the proper location of the email template. [5 points]
- Write this content to the Email
  => beginning where directed in the Mail Template 
 => filling in the email address (Use YOUR email address for testing), the manager name for <<Manager Name>>, and the complete filtered table for that Manager <<insert table here>>  [5 points]
- Email the message to your instructor at hoeke@usf.edu email address (only when FINAL - TEST runs should only go to your EMAIL address) [5 points]
⦁	DEBUGGING messages
- Display the Manager for which the email is constructed and the current date/time
- At the conclusion of the 3 emails - Display a message to the User "FINI" + current date/time and write this same message to the Output panel [5 points]
⦁	Submit the project XAML file [5 points]
Use the following naming convention <Last Name - First Name> - RPA_09.xaml
[NOTE: if you are NOT using UiPath, submit the equivalent project file]
⦁	Submit a DOCUMENT containing screen captures of the Studio showing your project flow (multiple FLOWCHART Activities - one for each subsection) [5 points]
⦁	Run the project
SUBMIT the Notepad document result [see above]
SUBMIT a screen capture of the Studio Output panel showing the results and your debugging comments [see above]
