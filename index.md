Here is a complete, step-by-step guide with the exact terminal commands you need to complete Assignment 1.3 and create your submission record.

Step 1: Open the Terminal
Windows: Open Command Prompt, PowerShell, or the integrated terminal in VS Code.

macOS / Linux: Open the Terminal app.

Step 2 to 4: Create the Folder Structure & Files using Terminal Commands
Run the following commands one by one (or copy-paste them) in your terminal. These commands create the main folder, navigate into it, create the weekly subfolders, and place an index.html file inside each one.

Bash

# 1. Create the main project folder
mkdir web-development-practice

# 2. Navigate inside the folder
cd web-development-practice

# 3. Create the week folders
mkdir week-1 week-2 week-3

# 4. Create an index.html file inside each week folder
# (For Windows PowerShell or Mac/Linux:)
echo "" > week-1/index.html
echo "" > week-2/index.html
echo "" > week-3/index.html

Note for Windows Command Prompt (cmd) users: If you are using standard Command Prompt instead of PowerShell, use type nul > folder_name/index.html instead of the echo command.

Step 5: Practice Navigation, Renaming, and Deleting (Optional Practice)
To show you practiced navigation and manipulation as required by the assignment, try these commands:

Navigate around:

Bash

cd week-1       # Go into week-1 folder
cd ..           # Go back up to web-development-practice


Rename a folder:

Windows (PowerShell): Rename-Item week-3 week-three

Mac/Linux: mv week-3 week-three

Delete a folder / file:

Remove a file: rm week-1/index.html (or del on Windows CMD)

Remove a folder: rmdir week-1 (or rm -rf week-1 on Mac/Linux)

(Make sure to recreate them if you deleted them for your final setup!)

Step 6: Open the Project in VS Code from the Terminal
To open your entire project directly in Visual Studio Code via the terminal, run:

Bash
code .
(Note: If this command gives an error, open VS Code manually, go to the Command Palette (Ctrl+Shift+P or Cmd+Shift+P), type "Shell Command: Install 'code' command in PATH", and try again).
