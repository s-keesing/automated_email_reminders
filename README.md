# automated_email_reminders

This is a script that will send out automated emails from the shift schedule spreadsheet reminding collaborators on the day that they have a shift. The function call needs to be updated once a month with the API address for the current month's spreadsheet.

Instructions for updating the API
1. Once you have created your spreadsheet in the correct format, go to "https://dashboard.sheety.co/" and log in with username admx.shift.manager@gmail.com and the password axionsrock
2. Click the upload button on the left-hand side of the screen and switch the tab to Google Sheets; click proceed, sign in with your credentials, and then allow cookies. Click on the spreadsheet you want to upload and choose "select."
3. The API address with appear. Paste it into the function call at the bottom of the email_script.
