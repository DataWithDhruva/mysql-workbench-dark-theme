# mysql-workbench-dark-theme
MySQL Workbench Dark Theme

This repository contains a custom dark theme for MySQL Workbench. The theme is applied by replacing the contents of the code_editor.xml file.

Installation
Copy the code from the code_editor.xml file in this repository.
Open This PC and go to the Local Disk (C:).
Open Program Files → MySQL → MySQL Workbench (the folder name may include a version number, e.g., MySQL Workbench 8.0).
Open the data folder.
Locate the file code_editor.xml and open it with Visual Studio Code.
Select all existing content (Ctrl + A) and delete it.
Paste the code you copied in step 1.
Save the file (Ctrl + S).
When the “Failed to save – Insufficient permissions” message appears, click Retry as Admin... and confirm.
Close MySQL Workbench completely and reopen it to see the new dark theme.
Troubleshooting
Cannot save the file? Make sure you click Retry as Admin..., since files in Program Files require administrator rights.
Theme not applied? Restart MySQL Workbench fully (check that it isn’t still running in the Task Manager).
Want to revert? Make a backup copy of the original code_editor.xml before replacing it, so you can restore it anytime.
