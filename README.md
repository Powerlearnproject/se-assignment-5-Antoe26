[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277517&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.'


STEPS TO DOWNLOAD AND INSTALL VS CODE

Open your web browser and go to the official Visual Studio Code website: Visual Studio Code.
Download the Installer

Click on the "Download" button for Windows. This will download the installer executable (.exe) file for VS Code.
Run the Installer:

Once the download is complete, locate the downloaded file (usually in the Downloads folder) and double-click on it to run the installer.

START INSTALLATION PROCESS:

The VS Code Setup Wizard will open. Click on the "Next" button to proceed.
Accept the License Agreement:

Read the license agreement. If you agree to the terms, select "I accept the agreement" and click "Next".

CHOOSE THE INSTALLATION LOCATION:
Select the destination folder where you want to install VS Code. The default location is usually fine. Click "Next" to continue.


SELECT ADDITIONAL TASKS:

You can select additional tasks such as creating a desktop icon, adding "Open with Code" action to Windows Explorer file context menu, and more. These options are helpful for easier access and integration. Select the options you prefer and click "Next".
Install:

Click on the "Install" button to begin the installation. The setup will copy the necessary files and install VS Code on your computer.

LAUNCH VISUAL STUDIO CODE:

Once the installation is complete, you can choose to launch VS Code immediately by checking the "Launch Visual Studio Code" box and clicking "Finish".



PREREQUISITES:

System Requirements:
Windows 11.
Administrator privileges for installation.


![visual studio setup Screenshot]( D:/se-assignment-1-setting-up-your-developer-environment-Antoe26/visual_studio_screenshot.png)




2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.





Initial Configurations
Theme and Icon Pack:

Theme: Customize the appearance by going to File > Preferences > Color Theme or pressing Ctrl+K Ctrl+T. Popular themes include "Dark+ (default dark)", "Light+ (default light)", and third-party themes like "One Dark Pro" or "Dracula Official".

Auto Save:

Enable auto-saving of files by searching for Files: Auto Save in the settings and setting it to afterDelay.
Tab and Indentation Settings:

Configure tab and indentation settings in the settings.
Editor: Tab Size -> 2 or 4 (based on your preference or project requirements)
Editor: Insert Spaces -> true (converts tabs to spaces)


Default Terminal:

Set the default terminal by searching for Terminal: Integrated: Shell: Windows and specifying the shell you prefer (e.g., PowerShell, Command Prompt, Git Bash).


IMPORTANT EXTENSIONS

Language Support:

Python: Provides rich support for the Python language, including features like IntelliSense, linting, debugging, code formatting, and more.
Prettier: An opinionated code formatter that supports multiple languages.

Debugger for Chrome: Debug your Python code running in the Chrome browser directly from VS Code.



Live Server: Launch a local development server with live reload feature for static and dynamic pages.

Path Intellisense: Autocompletes filenames in your code.




3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.





ACTIVITY BAR

Purpose:
Provides quick access to core functionality and different views.
Contains icons for switching between views such as Explorer, Search, Source Control, Run and Debug, and Extensions.

SIDE BAR

Purpose:
Displays contextual information and tools related to the selected activity from the Activity Bar.
Helps manage files, perform searches, view source control changes, and handle extensions.


EDITOR GROUP

Purpose:
Main workspace for writing and editing code.
Supports multiple tabs and split views for editing multiple files simultaneously.
Provides features like syntax highlighting and IntelliSense for a better coding experience.

STATUS BAR

Purpose:
Shows status information about the current workspace and active file.
Displays useful information such as Git branch, cursor position, language mode, and errors or notifications.






4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.


The Command Palette in Visual Studio Code is a powerful tool that provides quick access to a wide array of commands and features. It allows users to execute commands, perform tasks, and navigate through VS Code without using the mouse.

How to Access the Command Palette

Shortcut: Press Ctrl+Shift+P (or F1).

Menu: Go to View > Command Palette.

Examples of Common Tasks Using the Command Palette
Open a File:

Command: >Open File...
Usage: Quickly open any file in the workspace by typing its name.
Open Settings:

Command: >Preferences: Open Settings
Usage: Access and modify VS Code settings.
Install Extensions:

Command: >Extensions: Install Extensions
Usage: Search for and install new extensions.

Git Commands:

Command: >Git: Clone
Usage: Clone a Git repository.
Command: >Git: Commit
Usage: Commit changes to the repository.









5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.



Extensions in Visual Studio Code (VS Code) enhance and customize the functionality of the editor. They allow users to add new features, support for additional languages, debuggers, tools, themes, and more. Extensions can significantly improve productivity by providing functionalities that are not available out of the box.

Installing Extensions

Command Palette: Press Ctrl+Shift+P, type Install Extensions, and select it to open the Extensions view with the search bar.

Managing Extensions

Enable/Disable: In the Extensions view, right-click on an extension to enable or disable it.
Update: When updates are available, an Update button will appear next to the extension.
Uninstall: Right-click on the extension in the Extensions view and select "Uninstall" to remove it.


ESSENTIAL EXTENSIONS FOR WEB DEVELOPMENT
A)Live Server

Provides a local development server with live reload capability, making it easy to see changes in real-time.

B)Prettier - Code Formatter

An opinionated code formatter that supports many languages. It enforces a consistent style by parsing code and re-printing it with its rules.

C)ESLint

Integrates the ESLint JavaScript linter into VS Code, helping to find and fix problems in your JavaScript code.

D)Debugger for Chrome

Enables debugging of JavaScript code running in the Google Chrome browser directly from VS Code.

E)HTML CSS Support

Adds IntelliSense support for CSS class names and IDs in HTML files.

F)Path Intellisense

Provides auto-completion for filenames, making it easier to navigate and include files

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?



Opening the Integrated Terminal:

Open VS Code.

To open the integrated terminal, you have a few options:

Use the keyboard shortcut: Ctrl+`` (backtick) on Windows/Linux or Cmd+`` (backtick) on macOS.
You can also open it from the menu by going to View > Terminal.
Another way is by right-clicking in the editor or on a file in the Explorer and selecting Open in Terminal.



Using the Integrated Terminal:

Once the terminal is open, you can type commands as you would in any command-line interface (CLI).
You can navigate directories (cd command), run scripts (npm, python, etc.), execute system commands, and more.
It supports common keyboard shortcuts like Ctrl+C for interrupting commands, scrolling using the mouse wheel or keyboard, and copy-pasting text.


External Terminal vs. Integrated Terminal:

External Terminal Advantages: Sometimes an external terminal might be preferred for certain tasks, such as when you need more space or want to keep VS Code focused purely on editing.

Integrated Terminal Advantages: Offers convenience, faster context switching, and better integration with VS Code’s features like debugging and task running.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?




Creating a New File:

From the Explorer:
Open the Explorer by clicking the file icon on the Activity Bar or pressing Ctrl+Shift+E.
Right-click on the folder where you want to create the new file.
Select "New File" and enter the file name.

Using Command Palette:
Open the Command Palette by pressing Ctrl+Shift+P.
Type > New File and press Enter.

Creating a New Folder:

From the Explorer:
Open the Explorer (Ctrl+Shift+E).
Right-click on the parent folder.
Select "New Folder" and enter the folder name.
Opening Files and Folders in VS Code

Opening a File:

From the Explorer:
Click on the file name in the Explorer panel.
Using Command Palette:
Press Ctrl+P.
Start typing the file name and select it from the list.

Opening a Folder:

Using the Menu:
Go to File > Open Folder.
Browse to the desired folder and select it.

Using Command Palette:
Open Command Palette (Ctrl+Shift+P).
Type > Open Folder and press Enter.


MANAGING FILES AND FOLDERS IN VS CODE

Renaming Files and Folders:

From the Explorer:
Right-click on the file or folder.
Select "Rename" and enter the new name.


MOVING FILES AND FOLDERS:

From the Explorer:
Drag and drop the file or folder to the new location within the Explorer.
Deleting Files and Folders:

From the Explorer:
Right-click on the file or folder.
Select "Delete".
Navigating Between Files and Directories

Using Quick Open:

Press Ctrl+P and start typing the file name to quickly open it.

Using Go to File:

Press Ctrl+Shift+E to focus on the Explorer, then navigate through files using the arrow keys and Enter to open.

Using Keyboard Shortcuts:

Switch between open files: Ctrl+Tab or Ctrl+Shift+Tab.
Open previous editor: Ctrl+-.
Open next editor: Ctrl+Shift+-.

Using the Command Palette:

Press Ctrl+Shift+P to open the Command Palette and type commands to quickly navigate or perform actions.








   

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.


Opening the Settings:

Using the Menu:

Go to File > Preferences > Settings (or Code > Preferences > Settings on macOS).

Using Keyboard Shortcut:

Press Ctrl+, (Control key and comma).

Changing the Theme
Using the Settings UI:

Go to File > Preferences > Color Theme (or Code > Preferences > Color Theme on macOS).
Select a theme from the list.

Using Command Palette:

Press Ctrl+Shift+P to open the Command Palette.
Type > Preferences: Color Theme and select a theme.

Changing the Font Size

Using the Settings UI:

Open Settings (Ctrl+,).
Search for Font Size.
Adjust the Editor: Font Size setting to the desired value.

Customizing Keybindings

Accessing Keybindings:

Using the Menu:
Go to File > Preferences > Keyboard Shortcuts (or Code > Preferences > Keyboard Shortcuts on macOS).
Using Command Palette:
Press Ctrl+Shift+P.
Type > Preferences: Open Keyboard Shortcuts and select it.
Changing Keybindings:

Search for the command you want to change.
Click on the existing keybinding or the plus icon (+) next to the command.
Press the new key combination you want to assign.









9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?


Install necessary extensions for the language you're working with (e.g., Python, JavaScript, C++) from the Extensions view (Ctrl+Shift+X).
Open Your Project:

Open VS Code.
Go to File > Open Folder and select your project folder.
Create a Simple Program:

Create a new file (e.g., app.js for JavaScript, app.py for Python).


Configure the Debugger:

Open the Run and Debug view by clicking the Run icon in the Activity Bar or pressing Ctrl+Shift+D.

Click on "create a launch.json file" to open the launch.json configuration file.

Select the environment for your project (e.g., Node.js for JavaScript).


Set Breakpoints:

Open your source code file (e.g., app.js).

Click in the gutter to the left of the line number where you want to set a breakpoint. A red dot will appear to indicate the breakpoint.

Start Debugging:

In the Run and Debug view, select the configuration you created (e.g., "Launch Program").
Click the green play button or press F5 to start debugging.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Open Your Project in VS Code:

Go to File > Open Folder and select your project folder.
Initialize a Git Repository:

Open the Source Control view by clicking the Git icon on the Activity Bar or pressing Ctrl+Shift+G.
Click on "Initialize Repository" if prompted.

Alternatively, open the integrated terminal (`Ctrl+``) and run: git init #command

MAKING COMMITS
Stage Changes:

In the Source Control view, you will see all untracked and modified files.
Click the plus icon (+) next to each file to stage it. To stage all changes, click the plus icon in the "Changes" header.
Write a Commit Message:

In the "Message" box at the top of the Source Control view, type a descriptive commit message.
Commit Changes:

Click the checkmark icon (✔) above the "Message" box to commit the staged changes.

Alternatively, use the integrated terminal:

git add .
git commit -m "Your commit message"


ushing Changes to GitHub
Create a Repository on GitHub:

Go to GitHub and sign in.
Click the plus icon in the top-right corner and select "New repository."
Fill in the repository name and other details, then click "Create repository."
Add the Remote Repository:

Copy the repository URL from GitHub (e.g., https://github.com/username/repository.git).
In VS Code's integrated terminal, run:

git remote add origin https://github.com/username/repository.git
Push Changes to GitHub:

Push your local commits to GitHub by running:

git push -u origin master
Alternatively, you can use the Source Control view:
Click on the "..." (ellipsis) icon for more actions.
Select "Push."









 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

