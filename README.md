[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15253171&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

 **Kelvin Njuguna**
 **njugunak349@gmail.com**

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.


**Prerequisites**
- Ensure your system is running Windows 11.
- Ensure you have a stable internet connection.

**Steps to Download and Install Visual Studio Code**

-Visit the Official Website:
   - Go to [Visual Studio Code](https://code.visualstudio.com/).

-Download the Installer:
   - Click "Download for Windows" on the homepage.

-Run the Installer:
   - Double-click the downloaded file (e.g., `VSCodeSetup-x64-<version>.exe`).

-Follow the Setup Wizard:
   - Click "Next" to begin.
   - Accept the license agreement.
   - Choose the installation location (default is fine).
   - Select additional tasks (e.g., desktop icon, adding to PATH).
   - Click "Install."

-Complete Installation:
   - Optionally, launch Visual Studio Code immediately by checking the "Launch" box.
   - Click "Finish."

-First Launch:
   - Open Visual Studio Code from the Start menu or desktop icon.

Configure settings afterwards based on your preference.





2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

**CONFIGURATIONS**

-Theme and Font:
   - Theme: `File > Preferences > Color Theme`
   - Font: `File > Preferences > Settings`, search "Font Family"
-Editor Settings:
   - Tab Size: `Editor: Tab Size`
   - Format on Save: `Editor: Format On Save`
-Auto-Save:
   - Enable via `File > Auto Save`
-Settings Sync:
   - Sync with GitHub via `Settings Sync`

**EXTENSIONS**
-Language Support:
   - Python: `Python`
   - JavaScript/TypeScript: `ESLint`, `Prettier`
   - C++: `C/C++`
   - Java: `Java Extension Pack`


-Productivity:
   - `Live Server` This will help you see the output as you code.








3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.


**MAIN COMPONENTS OF THE VS CODE INTERFACE**

a) Activity Bar:
   - Located on the left side
   - Switches between views like Explorer, Search, Source Control, Run and Debug, and Extensions
b) Side Bar:
   - Located next to the Activity Bar
   - Displays contents of the selected view, such as the project directory or search results
c) Editor Group:
   - Located in the center
   - Serves as the main area for editing code, supporting multiple tabs and split views
d) Status Bar:
   - Located at the bottom
   - Shows current editor status, including branch, line/column number, language mode, and errors/warnings, and provides quick access to settings






4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette in Visual Studio Code (VS Code) is a feature that allows you to quickly access a wide array of commands and features. It's essentially a search interface for VS Code commands, enabling you to perform tasks without navigating through menus or remembering keyboard shortcuts.

To access the Command Palette:
1. Use the keyboard shortcut `Ctrl+Shift+P`.
2. Alternatively, you can select `View` > `Command Palette` from the menu bar.

Some common tasks you can perform using the Command Palette:
- Opening files:          Quickly open any file in your workspace by typing part of its name.
- Changing themes:        Switch between different color themes or file icon themes.
- Managing extensions:    Install, disable, or uninstall VS Code extensions.
- Running tasks:          Execute configured tasks like build or test scripts.
- Refactoring code:       Access refactoring options like rename symbol or format document.
- Navigating code:        Jump to a specific line, symbol, or file within your project.
- Controlling Git:        Perform Git operations like commit, push, pull, or switch branches.
- Debugging:              Start or stop debugging sessions, add breakpoints, and navigate through the call stack.

The Command Palette streamlines your workflow by putting all these commands at your fingertips, making it an essential tool for efficient coding in VS Code³⁴⁵.

**Source**
 VS Code: The command palette. https://thevalleyofcode.com/vscode/9-the-command-palette.






5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Extensions in Visual Studio Code (VS Code) serve to enhance and customize the development environment beyond the core functionalities. They allow you to add new languages, debuggers, and tools to your installation, supporting a more efficient and tailored development workflow. Extension authors can plug directly into the VS Code UI and contribute functionality through the same APIs used by VS Code.

To find, install, and manage extensions in VS Code, these steps can be followed:
-Find Extensions:   Open the Extensions view by clicking on the Extensions icon in the Activity Bar or by using the `Ctrl+Shift+X` shortcut. This will display a list of the most popular extensions on the VS Code Marketplace.

-Install Extensions:  Select an extension from the list to view its details and click the 'Install' button. Once installed, the button will change to a 'Manage' gear button.

-Manage Extensions:  Installed extensions can be managed by clicking the 'Manage' gear button, where you can configure settings, disable, or uninstall the extension.


For web development, some essential extensions include:
- JavaScript (ES6) Code Snippets: Provides code snippets for JavaScript, TypeScript, Vue, React, and HTML, which can save time on writing repetitive code¹.

- Auto Close Tag: Automatically adds closing tags for HTML and XML, speeding up markup writing.

- Prettier: An opinionated code formatter that ensures consistent code style across your project.
-HTML Snippets:  Provides a collection of HTML snippets for quick and easy coding.


**Source**
(a) 10 must-have VS Code extensions for web development - Coding Beauty. https://www.codingbeautydev.com/blog/vscode-extensions-for-web-development.
(b) 31 Best VS Code Extensions for Web Development. https://marketplace.visualstudio.com/items?itemName=DevDas.best-code-extensions-for-web-development.





6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

To open the integrated terminal, go to the menu bar and select View > Terminal.

The integrated terminal is convenient as it allows you to run commands and access the command line interface without leaving VS Code. It’s context-aware, meaning it automatically sets the working directory to your current project folder. Additionally, it supports theme integration for a consistent look with your editor, and it’s fully customizable. Compared to an external terminal, it streamlines your workflow by keeping all your tools in one place and reduces the need to switch between different windows or applications.

The integrated terminal in VS Code offers several advantages over an external terminal:

-Convenience: It allows you to run terminal commands without leaving the editor, streamlining your workflow.
-Context Awareness: The working directory is automatically set to the project folder you’re working in.
-Theme Integration: The terminal’s appearance matches your VS Code theme for a consistent look and feel.
-Customization: You can customize settings like the shell, fonts, and scrollback to suit your preferences.
-Multiple Instances: Support for multiple terminal instances makes it easier to manage different tasks simultaneously.









7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

**MANAGING FILES**

Creating Files and Folders
- Creating a File:
  1. Open VS Code.
  2. Use the Explorer view (Activity Bar icon or `Ctrl+Shift+E`) to navigate to the desired directory.
  3. Right-click on the directory or use the context menu (`Ctrl+Click` on macOS) and select `New File`. Enter a filename with an appropriate extension (e.g., `.js`, `.py`).

- Creating a Folder:
  1. Follow the same steps as creating a file but choose `New Folder` from the context menu. Enter a folder name.

Opening Files and Folders
- Opening Files:
  - Double-click on a file in the Explorer view to open it in the editor. Alternatively, use the `File > Open File...` menu (`Ctrl+O`) to navigate to a file and open it.

- Opening Folders:
  - Use `File > Open Folder...` to open an entire folder as a workspace in VS Code. This allows access to all files and subdirectories within that folder.

Managing Files and Folders
-Renaming Files/Folders:
  - Right-click on a file or folder in the Explorer view and choose `Rename` to change its name.

- Deleting Files/Folders:
  - Right-click on a file or folder and select `Delete` to remove it. Be cautious as this action is irreversible without version control.

NAVIGATING BETWEEN FILES AND FOLDERS
- Using the Explorer View:
  - Click on files and folders in the Explorer view to switch between them.

- Navigating with Keyboard Shortcuts:
  - Use `Ctrl+P` to open the Quick Open dialog, type the filename, and press `Enter` to open it quickly.

- Navigating Back and Forward:
  - Use `Alt+Left Arrow` to navigate back and `Alt+Right Arrow` to navigate forward through recently opened files.

- Using Tabs:
  - Open multiple files in tabs within the editor. Click on a tab to switch between open files.

- Searching for Files:
  - Use the Search view (`Ctrl+Shift+F`) to search for files within the current workspace.











8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

In Visual Studio Code (VS Code), users can find and customize settings by following these steps:

Open the Command Palette with Ctrl+Shift+P.
Type Preferences: Open Settings (UI) and select it to open the settings interface.
Alternatively, you can navigate to File > Preferences > Settings.

Here are examples of how to change the theme, font size, and keybindings:

Change the Theme:
-Open the Command Palette.
-Type Preferences: Color Theme and select it.
-Browse through the list of themes and select one to apply.

Change the Font Size:
-Go to the settings UI as mentioned above.
-Search for Editor: Font Size in the search bar.
-Enter the desired font size in the input box that appears.

Change Keybindings:
-Open the Command Palette.
-Type Preferences: Open Keyboard Shortcuts (UI) and select it.
-Here you can search for the command you want to change the keybinding for and set a new shortcut.


**Source**
https://cohttps://code.visualstudio.com/docs/getstarted/themesde.visualstudio.com/docs/getstarted/themes





9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

To set up and start debugging a simple program in VS Code;

1. Open your project in VS Code.
2. Set a breakpoint by clicking on the left margin next to the line numbers where you want the execution to pause.
3. Open the Run and Debug view by clicking on the Run and Debug icon in the Activity Bar or using the shortcut `Ctrl+Shift+D`.
4. Create a launch.json file by clicking on 'create a launch.json file' in the Run and Debug view. This file contains configuration settings for your debugging session.
5. Select the appropriate environment for your application (like Node.js, Python, etc.) when prompted.
6. Start debugging by pressing `F5` or clicking the green play button. VS Code will try to run your currently active file with the debug configuration specified in launch.json.

Key debugging features in VS Code include:

- Breakpoints:          Set, disable, or remove breakpoints to control the execution flow.
- Variable Inspection:  Hover over variables to see their current values or use the Variables pane in the sidebar.
- Step Over/Into/Out:   Navigate through your code one line or function at a time.
- Call Stack:           View the call stack to see the function call hierarchy.
- Watch Expressions:    Evaluate expressions on the fly and watch their values change in real-time.
- Debug Console:        Execute commands and evaluate expressions in the context of the debugging session.

**Source**
(a) Debugging in Visual Studio Code. https://code.visualstudio.com/Docs/editor/debugging.
(b) How to Debug in Visual Studio Code - Coding Campus. https://codingcampus.net/how-to-debug-in-visual-studio-code/.







10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

   
   
   
    Integrating Git with VS Code for version control involves a few steps;
**Initializing a Repository**:
1. Open a Folder: Open the folder you want to version control in VS Code.
2. Initialize: In the Source Control view, click the 'Initialize Repository' button to create a new Git repository in that folder.

**Making Commits**:
1. Make Changes: Edit your files in VS Code as needed.
2. Stage Changes: In the Source Control view, stage the changes you want to include in your commit.
3. Commit: Type a commit message and press `Ctrl+Enter`to commit the staged changes.

**Pushing Changes to GitHub**:
1. Add Remote: Link your local repository to a GitHub repository using the `Git: Add Remote` command from the Command Palette.
2. Push: Use the 'Push' action in the Source Control view to send your commits to the remote repository on GitHub.

**Source**
(a) Introduction to Git in VS Code - Visual Studio Code. https://code.visualstudio.com/docs/sourcecontrol/intro-to-git.
(b) Using Git source control in VS Code - Visual Studio Code. https://code.visualstudio.com/docs/sourcecontrol/overview.
(c) How to add a new project to Github using VS Code. https://stackoverflow.com/questions/46877667/how-to-add-a-new-project-to-github-using-vs-code.

    









 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

