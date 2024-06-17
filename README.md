[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15269398&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
Answer.
Prerequisites.
Make sure you have windows 11 installed and running on your computer.
Have a good internet connection to enable you to download the Visual Studio Code installer.
Downloading and installing Visual Studio Code.
Visit Visual Studio Code official website. Or follow the download link https://code.visualstudio.com/Download.
Click the Windows button .
Open the downloaded file once the download is complete (VSCodeSetup.exe) and run the installation file.
Follow the setup wizard: Accept the licence agreement  and click “Next”.
Choose the location for installation (choose the default folder C:\Users\Program Files\Microsoft VS Code) and click “Next.
Select any additional tasks such as creating a desktop icon and  adding VS Code to the PATH and click “Next”.
Click on “install” to complete the installation.
Once the installation is complete click on “Finish” to launch VS Code.



2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
Answer.
Install essential extensions to enhance VS Code functionality. These include: python, pychat, prettier, html-css support, code runner, java, docker e.t.c. Navigate to the activity bar and click the extensions icon or press Ctrl+Shift+X on your keyboard, on the search bar type the extension you need the click install.
Adjust user settings to customise VS Code to your preference.
On the activity bar click the settings icon or go to “File>Preferences>Settings.” Click Ctrl+Shift+p to open the command palette.
Select a theme from ‘Settings>Themes>Color theme’. 
You can adjust several things to your preference i.e Auto save, Font size,Word Wrap, Tab size e.t.c 
Configure your extensions.
Open the command palette (Ctrl+Shift+p). Select the extension; i.e “python: select interpreter “ to choose the correct python interpreter.
Set up source control.
Integrate Git into your VS Code. If git is already installed in your computer VS Code will recognize it.
You can customise keyboard shortcuts.
Configure the integrated terminal by changing the default shell to your preferred shell like GitBash or PowerShell.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
Answer.
Activity bar.
It is located on the vertical bar on the far left side of the window.
It provides access to different tools and views where each icon represents a different view. I.e  
Explorer for navigating and managing files and folders.
Search icon for searching text within the workspace.
Run and Debug for managing debugging sessions.
Extensions for adding and managing extensions.
Source control for version control operations.
Settings for adjusting your VS Code to your preference.
Views from installed extensions can also appear e.g GitHub, Docker e.t.c.
Side bar.
It is located to the right of the activity bar and displays contents related to the view that has been selected on the activity bar. E.g Search displays search results, extensions displays list of installed extensions, explorer displays the file and folder structure of the workspace. 
Editor group.
It is the central window of VS Code where you write and edit your code. Multiple editors can be open on VS Code simultaneously. 
Each opened file appears as a new editor tab to the right and opened editors go into the same editor group. To group similar files or allow side by side editing of the same file you can create new editor groups.
Status bar.
It is the horizontal bar at the bottom of the VS Code window and it provides information on the current workspace and the active file. I.e.
The file information such as the EOL sequence, the encoding and language mode.
The branch information which shows the current Git branch and sync status if a repository is open.
Notifications to indicate errors and warnings.
Line and column information showing the current cursor position.
Some extensions add their status indicators e.g a python environment indicator.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
Answer
The command palette is one of the most useful features in VS Code which gives you easy access to and execution of various commands. It offers a rapid method for completing a variety of operations without requiring the user to go through menus and settings.
You can access it by clicking the settings icon on the activity bar Settings > Command palette, pressing Ctrl+Shift+p on your keyboard or via the menu by selecting View > Command palette.
Common tasks performed by command palette i.e.
To open settings ‘Preferences: Open Settings (UI)’
To install extensions ‘Extensions: Install Extensions’
To open a file ‘File: Open File’
To run a task ‘Tasks: Run Task’
To change the colour theme ‘Preferences: Colour Theme’
To perform git operations e.g committing changes ‘Git: Commit’
To view all keyboard shortcuts on VS Code ‘Preferences: Open Keyboard Shortcuts’
To run a debugging session for the current project ‘Debug: Start Debugging’

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
Answer.
Extensions extend the functionality of VS Code and allow you to tailor the development environment to your own preference.It adds and supports new languages, tools, debuggers and several other features making VS Code a more potent and adaptable code editor.
You can find extensions by opening the extensions view by clicking on the extensions icon on the activity bay or pressing Ctrl+Shift+x on your keyboard. To find specific extensions type the name of the extension on the search bar at the top of the extensions view.
To install the extension, find the extension you want on the extensions view and click the “install” button to install.‘ You can also install them by using the command palette,open by Ctrl+Shift+p then type ‘Extensions: Install Extensions’ then search the extension you need and install it.
Managing extensions: 
Enable/disable by clicking the gear icon next to the extension name and selecting Enable or Disable.
Uninstall by clicking the gear icon next to the extension name then select Uninstall.
Updating; If there is an update to an extension there will be an update button next to the extension. Click it to update to the latest version.
Examples of extensions for web development: 
HTML CSS Support.
Debugger for chrome.
IntelliSense for CSS class names in HTML.
Prettier.
ESLint.
Path IntelliSense.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
Answer.
To open the terminal navigate to the top menu select View >Terminal or click the three dots > Terminal >New terminal. You can also use the keyboard shortcut ‘Ctrl+’ or ‘Ctrl+Shift+’. You can also use the command palette by opening the command palette then type ‘Terminal: Create New Terminal’.
Once open you can use it to: 
 Run commands by pressing enter after typing your commands.
To create new terminals by pressing the + icon in the terminal tab bar.
To switch between terminals by using the dropdown menu in the terminal tb bar.
To split terminals by clicking the icon next to the +icon in the terminal tab bar.
To close the terminal click on the trash can icon.
To hide the terminal panel click on the x icon.

Advantages of using the integrated terminal.
Provides seamless integration with the editor to support features like links and error detection.
Enhanced productivity as it allows you to manage multiple terminal sessions within the same window thereby you can run several operations simultaneously. It is also easy to open thereby saving time.
Allows for shell customization and configuration i.e. Command Prompt. PowerShell or GitBash.
It maintains its state as you can close and reopen VS Code without losing your terminal state.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
Answer.
Creating and opening files. 
To create a new file click the Explorer icon on the activity bar to open the explorer view or press ‘Ctrl+Shift+E’ on your keyboard and right click on the folder you want a new file created and select ‘New File’, enter the file name and press enter. You can also use the command palette ‘File: New File’ or the keyboard shortcut ‘Ctrl+N’
To open an existing file go to the explorer view and click on the file you want to open. Use the menu bar go to File > Open file and navigate to the file you want to open.
Creating and opening folders.
On the explorer view right click on the folder where you want a new folder created and select new folder, enter the folder name and press enter on your keyboard.
To open an existing folder go to File > Open Folder on the menu bar.
Managing files and folders.
Rename files and folders by right clicking on the file or folders and select ‘Rename’
Delete files and folders by right clicking on the file o folder then click ‘Delete’
Navigating between different files and folders efficiently.
Quick Open: Press Ctrl+P to open the Quick Open dialog box, type your file or folder name and select it from the list.
Explorer View: Navigate through the directory structure using the explorer view. Click on the file or folder to expand, collapse them and view their contents.
Command Palette.:  Press Ctrl+Shift+P, type File: , and select commands like File: Open Recent or File: Save All.
Use keyboard shortcuts i.e. Ctrl+Tab to switch between open tabs.
You can open multiple files within the editor as tabs.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
Answer.
To find settings, click on the gear icon on the lower left corner of the window and select Settings or press ‘Ctrl+,’. You can also open the command palette Ctrl+Shift+P then type ‘Preferences: Open Settings(UI)’
Changing theme: Click the gear icon on the activity bar then click Themes > Color theme or open command palette Ctrl+Shift+P then type ‘Preferences: Color Theme’
Changing font size: Open settings Ctrl+, then type ‘font size’ on the search bar, find the ‘Editor: Font Size’ setting and change value to your desired font size.
Changing keybindings: Open keyboard shortcuts editor by pressing Ctrl+Shift+S, on the search bar find the command you want to change the keybinding for, click on the current keybinding next to the command you want to change the press the new key combination you want to assign and press Enter.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
Answer.
Steps to set up and start debugging a simple program.
Install the relevant extensions from the extensions view.e.g python.
Create a new file for your program e.g app.py
Click the debug icon on the activity bar or press Ctrl+Shift+D.
Click the gear icon at the top of the debug panel and select the relevant environment e.g ‘python’ for python.
Set breakpoints by clicking in the gutter to the left of the line numbers in your code file and a red dot will appear to indicate your breakpoint.
Start debugging by clicking the green play button in the debug panel or press F5 to start debugging. The program will run and pause execution at the set breakpoint.
Key debugging features in VS Code.
Breakpoints: Click in the gutter next to the line numbers to set breakpoints.
Variables and watch: You can view the current values of variables in the variables panel in the debug sidebar, you can add expressions to watch their values as you step through your code, you can hover over variables in the editor to see their current values.
Step controls: F5(continue) to resume execution till the next breakpoint or end of the program, F10(step over) to execute the next line of code stepping over function calls, F11(step into) to step into the next function call and Shift+F11(step out) to step out of the current function back to the calling.
Call stack: View the call stack of your program showing the sequence of function calls that led to the current point in execution. Navigate the call stack by clicking on stack frames to view the state of your program at different levels of the call stack.
Debug console: Used to inspect and modify the state of your app during debugging.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
Answer.

Integrating Git into VS Code.
Download and install git into your computer and verify the installation by typing ‘git --version’ on the command prompt. 
Open VS Code and create a new project folder or open the folder containing your project.

Initializing a Git repository.
Open terminal, navigate to your project directory and run the command “git init” on your terminal

Making commits and pushing changes to GitHub.
Open your browser and sign in to your GitHub account.
Click the + icon at the top right corner and select ‘New Repository’, fill in the repository name , description (this is optional) and select the visibility either private or public then click ‘Create Repository’.
Click on ‘Code’ and copy the repository URL e.g “https://github.com/faridahkaberia/assignment-answers.git”.
Open the terminal on VS Code and add the remote repository using this command; “git remote add origin https://github.com/faridahkaberia/assignment-answers.git ”
To stage all files for commits run “git add .”
To commit changes, run “git commit -m “Initial commit””
To push your changes to GitHub repository run the command “git push -u origin main”. Note: if your default branch is ‘master’ use master in the command above instead of ‘main’.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

