[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282657&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
**Steps to Download and Install Visual Studio Code**
**Download VS Code Installer**
Open your preferred web browser and go to [https://code.visualstudio.com/download](https://)
Click on the Windows download button. This will download the VS Code installer.

**Run the Installer**
Once the download is complete, open the installer file. You can find it in your Downloads folder or the location you specified for downloaded files.
Double-click the installer file to start the installation process.

Select the workloads and components you need based on your development requirements. 

**Installation Wizard**
License Agreement: The installation wizard will open. Read and accept the license agreement by checking the I accept the agreement checkbox, then click Next.
Select Destination Location: Choose the destination folder where you want to install VS Code. The default location is usually fine, so click Next.
Select Additional Tasks: You will be prompted to select additional tasks:
Click Next after selecting your preferences.

**Installation**
Click the Install button to begin the installation. The installer will copy the necessary files to your system.
Once the installation is complete, you will see a Completing the Visual Studio Code Setup screen. Check the box for Launch Visual Studio Code if you want to open VS Code immediately after installation, and then click Finish.

**First Launch and Configuration**
If you chose to launch VS Code immediately, it will open. If not, you can open it from the Start menu or the desktop shortcut you created.
On the first launch, VS Code may prompt you to install additional components or extensions depending on your system and usage. Follow the prompts to complete any necessary setups.

Choose developer environment and start coding on VS Code.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

**Initial Configurations**
Choose a theme that is comfortable for your eyes. Popular themes include "Dark+ (default dark)", "Light+ (default light)", and extensions like "One Dark Pro" or "Dracula Official".

Install an icon theme like "Material Icon Theme" for better file and folder visualization.

Adjust the font size and family to your preference.

Adjust the line height for better readability. 

Set the tab size to match your coding style

Enable auto-saving to avoid losing work.

Enable automatic formatting on save.

Error Lens: Highlight errors and warnings inline.

Integrated Terminal Shell: Set your preferred shell.

Ensure extensions are always up-to-date.

**Essential Extensions**
**Code Formatting and Linting**
Prettier: Code formatter for a wide variety of languages.
ESLint: Integrates ESLint into VS Code for JavaScript/TypeScript linting.

**Version Control**
GitLens: Supercharge the built-in Git capabilities with visual aids and insights.
GitHub Pull Requests and Issues: Integrate GitHub PRs and issues into VS Code.

**Language Support**
Python: Microsoft's Python extension for rich Python support.
Pylance: Fast, feature-rich language support for Python.
JavaScript/TypeScript: Built-in support, enhanced by extensions like ESLint and Prettier.
Java: "Language Support for Java(TM) by Red Hat".
C/C++: "C/C++" by Microsoft.
Go: "Go" extension by the Go team.
Rust: "rust-analyzer" for Rust language support.

**IntelliSense and Snippets**
Visual Studio IntelliCode: AI-assisted IntelliSense.
Path IntelliSense: Autocompletes filenames.
Snippets: Install snippets for your preferred languages (e.g., "JavaScript (ES6) code snippets").

**Docker and Containers**
Docker: Tools for managing Docker containers.
Remote - Containers: Develop inside a container using Docker.

**Debugging and Testing**
Debugger for Chrome: Debug your JavaScript code running in Chrome directly from VS Code.
Python Test Explorer: For running and debugging Python tests.

**Remote Development**
Remote - WSL: Development in the Windows Subsystem for Linux.
Remote - SSH: Connect to and develop on remote machines.

**Other Useful Extensions**
Live Server: Launch a development local server with live reload feature for static & dynamic pages.
Todo Tree: Highlight and manage TODO comments in your code.
Bracket Pair Colorizer 2: Colorizes matching brackets.


**Configuring Extensions**
Prettier
ESLint
Customize keybindings to your workflow. Common changes include Toggle Sidebar and Format Document


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
**Activity Bar**
The Activity Bar is located on the far left side of the VS Code window. It allows you to switch between different views and gives you access to important features.
Icons and Functions: The Activity Bar contains icons for different activities such as Explorer, Search, Source Control, Run and Debug, Extensions, and more. Each icon represents a different view or tool.
Customization: You can customize the Activity Bar by dragging icons to rearrange them or right-clicking to hide/show specific icons.

**Side Bar**
The Side Bar is adjacent to the Activity Bar and provides additional context and tools based on the selected activity.
Explorer: Shows your project files and folders, allowing you to navigate and manage your project's structure.
Search: Allows you to search across files in your workspace.
Source Control: Integrates with version control systems like Git, displaying changes, branches, and repositories.
Extensions: Allows you to browse, install, and manage extensions to enhance VS Code functionality.
Other Views: Depending on the installed extensions, other views like Docker, Remote Explorer, etc., may appear here.

**Editor Group**
The Editor Group is the main area where you write and edit your code. This component is highly customizable and supports multiple tabs and split views.
Tabs: Each open file is represented by a tab at the top of the Editor Group. You can switch between files by clicking on these tabs.
Split Editors: You can split the Editor Group into multiple sections either vertically or horizontally, allowing you to work on multiple files side by side.
Features: The Editor Group includes features like syntax highlighting, IntelliSense (code suggestions), debugging, and more.

**Status Bar**
The Status Bar is located at the bottom of the VS Code window and provides information and controls relevant to your current context.
Information Display: The Status Bar displays various pieces of information, such as the current Git branch, line and column numbers, encoding, file type, and more.
Interactive Elements: Many elements on the Status Bar are interactive, allowing you to click on them to change settings or view additional information (e.g., changing the language mode of the current file).
Notifications and Errors: Displays notifications, errors, and warnings related to your project.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
**Accessing the Command Palette**
The Command Palette can be accessed in two main ways:
Keyboard Shortcut:
Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Menu:
Go to the menu bar and select View > Command Palette.

**Common Tasks Performed Using the Command Palette**
**Opening Files and Folders**
Open File: Type >Open File and select the file you want to open.
Open Folder: Type >Open Folder to open a folder in VS Code.

**Managing Extensions**
Install Extension: Type >Extensions: Install Extensions to browse and install new extensions.
Disable Extension: Type >Extensions: Disable and select the extension you want to disable.

**Running and Debugging Code**
Run Task: Type >Run Task to execute a pre-configured task.
Start Debugging: Type >Debug: Start Debugging to start a debugging session.

**Version Control**
Git: Clone: Type >Git: Clone to clone a repository from a URL.
Git: Commit: Type >Git: Commit to commit changes with a message.

**Code Editing and Navigation**
Go to Line: Type >Go to Line and enter a line number to navigate directly to that line.
Format Document: Type >Format Document to automatically format the entire document according to your settings.
Rename Symbol: Type >Rename Symbol to rename all instances of a symbol (e.g., a variable or function) in your code.

**Customizing the Editor**
Change Color Theme: Type >Preferences: Color Theme to switch between installed color themes.
Configure User Snippets: Type >Preferences: Configure User Snippets to create or edit code snippets.

**Searching and Replacing**
Find in Files: Type >Search: Find in Files to search for text across all files in your workspace.
Replace in Files: Type >Search: Replace in Files to replace text across all files.

**Terminal Management**
Create New Integrated Terminal: Type >Terminal: Create New Integrated Terminal to open a new terminal window within VS Code.
Run Active File in Terminal: Type >Run Active File to execute the current file in the integrated terminal.

**Examples of Using the Command Palette**
**Changing the Color Theme**
Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type Preferences: Color Theme.
Select your desired theme from the list.

**Formatting a Document**
Open the Command Palette.
Type Format Document.
The current document will be formatted according to your settings.

**Installing an Extension**
Open the Command Palette.
Type Extensions: Install Extensions.
Search for and install the desired extension.

**Committing Changes in Git**
Open the Command Palette.
Type Git: Commit.
Enter your commit message and press Enter.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
**Role of Extensions in VS Code**
**Finding Extensions**
Marketplace- VS Code has an integrated extension marketplace that can be accessed via the Extensions view.
Click on the Extensions icon in the Activity Bar on the side of the window or use the keyboard shortcut Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (Mac).
Search- Use the search bar within the Extensions view to find specific extensions by name or keyword.
The marketplace also categorizes extensions, making it easier to browse through popular, recommended, and trending extensions.

**Installing Extensions**
Via the Extensions View- Search for the desired extension.
Click the Install button next to the extension in the search results.
Via Command Palette- Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type Extensions- Install Extensions.
Search for and select the extension you want to install.
Manual Installation- Extensions can also be installed manually by downloading the .vsix file from the marketplace and installing it via the Extensions view by clicking on the ellipsis (three dots) in the top right corner and selecting Install from VSIX.

**Managing Extensions**
Enable/Disable- Installed extensions can be enabled or disabled via the Extensions view.
Right-click on an extension and choose Disable or Enable.
Uninstall- To uninstall an extension, click the Uninstall button in the Extensions view.
Right-click on the extension and select Uninstall.
Settings- Many extensions come with configurable settings that can be accessed via the Settings (gear icon) in the Extensions view or through the Command Palette by typing Preferences: Open Settings (UI).
Updates- Extensions are updated automatically by default, but you can manually check for updates in the Extensions view by clicking on the ellipsis (three dots) and selecting Check for Extension Updates.

**Essential Extensions for Web Development**
**Prettier - Code Formatter**
Automatically formats your code to ensure consistency.
Supports multiple languages including JavaScript, TypeScript, HTML, CSS, and more.
**ESLint**
Integrates ESLint into VS Code to provide JavaScript and TypeScript linting.
Helps in maintaining code quality by highlighting errors and warnings.
**Live Server**
Launches a local development server with live reload feature for static and dynamic pages.
Useful for real-time preview of your web applications during development.
**HTML Snippets**
Provides a collection of useful HTML snippets to speed up development.
Includes commonly used HTML boilerplate code.
**CSS Peek**
Allows you to view and quickly navigate to the CSS code relevant to your HTML elements.
Provides in-editor tooltips and navigation features.
**Path Intellisense**
Autocompletes file names and paths in your project.
Enhances productivity by reducing the time spent on typing and searching for file paths.
**Debugger for Chrome**
Enables debugging of JavaScript code running in the Google Chrome browser.
Provides a seamless debugging experience directly from VS Code.
**Bracket Pair Colorizer 2**
Colorizes matching brackets to make nested code structures easier to read.
Improves code readability and reduces errors related to mismatched brackets.
**JavaScript (ES6) Code Snippets**
Adds a set of JavaScript ES6 code snippets to boost productivity.
Includes snippets for commonly used code patterns and functions.
**REST Client**
Allows you to send HTTP requests and view responses directly within VS Code.
Useful for testing APIs without leaving the editor.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
**Opening and Using the Integrated Terminal in VS Code**
**Opening the Integrated Terminal**
Using Keyboard Shortcuts- Press Ctrl+ (Windows/Linux) or Cmd+ (Mac).
Using the Menu- Go to the menu bar and select View > Terminal.
Using the Command Palette:
Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type Terminal: Create New Integrated Terminal and press Enter.

**Using the Integrated Terminal**
Basic Operations- Create New Terminal: Click the plus (+) button in the terminal panel or use the Terminal: Create New Integrated Terminal command from the Command Palette.
Split Terminal- Click the split terminal button (split square icon) in the terminal panel to create a new terminal side by side with the existing one.
Switch Between Terminals- Use the dropdown menu in the terminal panel or keyboard shortcuts Ctrl+ and arrow keys to navigate between multiple terminals.
Resize Terminals-Drag the edges of the terminal panel to resize it or use the Ctrl+Shift+`` and Ctrl+Shift+ (or `Cmd+Shift+ and `Cmd+Shift+`` on Mac) to resize the terminal vertically.

**Customization**
Change Shell- You can change the default shell by adding or modifying the setting in your settings.json file.

Change Theme- The terminal will inherit the color theme of your editor, but you can further customize the colors using terminal-specific settings in settings.json.

**Running Commands**
Simply type your commands in the terminal and press Enter. The integrated terminal supports all standard command-line operations, such as navigating directories, running scripts, managing version control with Git, etc.

**Advantages of Using the Integrated Terminal Compared to an External Terminal**
**Seamless Integration**
The integrated terminal allows you to stay within the VS Code environment, reducing the need to switch between different applications. This enhances productivity by keeping all tools and windows in one place.
**Context Awareness**
The integrated terminal can automatically open in the root of your workspace or project directory. This ensures commands are run in the correct context without needing to manually navigate to the correct path.
**Synchronization**
The terminal can synchronize with VS Code features such as the Explorer, Source Control, and Debugging. For instance, you can view changes in the Source Control panel and immediately commit them using Git commands in the terminal.
**Multiple Terminals**
You can easily create and manage multiple terminals within the same window. This allows you to run different tasks simultaneously, such as running a development server in one terminal and a build process in another.
**Customizable Environment**
The integrated terminal can be customized to match your workflow preferences, including setting up different shells (Bash, Zsh, PowerShell, etc.), configuring fonts, colors, and other settings.
**Accessibility**
The terminal can inherit and adapt to VS Code's accessibility settings, making it easier for users with special needs to use the command line effectively.
**Unified Keybindings**
Using the integrated terminal ensures that keybindings and shortcuts are consistent across the editor and terminal, avoiding conflicts and confusion.

**Example Use Cases**
**Running Build Scripts**- Use the terminal to run build commands (e.g., npm run build or yarn build) while working on your code.
**Version Control**- Manage your Git workflow directly from the terminal (e.g., git status, git commit, git push), and see the changes reflected in the Source Control panel.
**Starting Development Servers**- Start your local development server (e.g., npm start or python -m http.server) without leaving the editor.
Executing Tests: Run your test suites (e.g., npm test, pytest) and see the results immediately.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
**Creating, Opening, and Managing Files and Folders in VS Code**
**Creating Files and Folders**
Using the Explorer View
Create a New File Open the Explorer view by clicking the Explorer icon in the Activity Bar or using the keyboard shortcut Ctrl+Shift+E (Windows/Linux) or Cmd+Shift+E (Mac).
Right-click on the folder where you want to create the new file and select New File, or use the New File button at the top of the Explorer.
Enter the name of the new file and press Enter.
Create a New Folder:
In the Explorer view, right-click on the location where you want to create the new folder and select New Folder, or use the New Folder button.
Enter the name of the new folder and press Enter.
Using the Command Palette:
Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Type >File: New File or >File: New Folder and follow the prompts.
Using Keyboard Shortcuts:
Ctrl+N (Windows/Linux) or Cmd+N (Mac) to create a new untitled file.
Save the new file with Ctrl+S (Windows/Linux) or Cmd+S (Mac) and specify the location and filename.

**Opening Files and Folders**
Using the Explorer View:
Navigate to the desired file or folder in the Explorer view and click to open it.
Double-clicking a file will open it in a permanent tab, while a single click will open it in a preview tab.
Using the Command Palette:
Open the Command Palette and type >File: Open File or >File: Open Folder.
Follow the prompts to navigate to and open the desired file or folder.
Using Keyboard Shortcuts:
Ctrl+O (Windows/Linux) or Cmd+O (Mac) to open a file.
Ctrl+K Ctrl+O (Windows/Linux) or Cmd+K Cmd+O (Mac) to open a folder.

**Managing Files and Folders**
Rename:
Right-click the file or folder in the Explorer view and select Rename.
Enter the new name and press Enter.
Move:
Drag and drop the file or folder to a new location within the Explorer view.
Delete:
Right-click the file or folder and select Delete, or select the file and press Delete on your keyboard.
Confirm the deletion if prompted.

**Navigating Between Different Files and Directories Efficiently**
**Explorer View**
Use the Explorer view to navigate through the directory structure visually.
Collapse and expand folders by clicking the arrow icons next to them.
**Quick Open**
Press Ctrl+P (Windows/Linux) or Cmd+P (Mac) to open the Quick Open feature.
Start typing the name of the file you want to open, and Quick Open will show a list of matching files. Select the desired file and press Enter.
**Go to Symbol**
Use Ctrl+Shift+O (Windows/Linux) or Cmd+Shift+O (Mac) to open the Go to Symbol feature within the current file.
Start typing the name of a symbol (e.g., function, class) to quickly navigate to its location in the file.
**Breadcrumbs**
Enable breadcrumbs by selecting View > Show Breadcrumbs from the menu.
Use the breadcrumbs at the top of the editor to navigate through the file's structure and its parent directories.
**File tabs**
Open multiple files in tabs at the top of the editor. Click on a tab to switch between files.
Use Ctrl+Tab to cycle through open files, and Ctrl+Shift+Tab to cycle in reverse order.
**Side-by-Side Editing**
Split the editor to view multiple files side by side by right-clicking a tab and selecting Split Right or Split Down.
Use the View: Split Editor command from the Command Palette.
**Keyboard Shortcuts**
Navigate between open files using Ctrl+Page Up/Page Down (Windows/Linux) or Cmd+Option+Left/Right (Mac).
Move between split panes using Ctrl+1, Ctrl+2, etc., depending on the pane number.

**Example Workflows**
**Quick File Opening**
Press Ctrl+P (Windows/Linux) or Cmd+P (Mac) and start typing the filename.
Select the file from the list and press Enter.
**Navigating to a Specific Function**
Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Type Go to Symbol in File... and start typing the function name.
Select the function from the list and press Enter.
**Using Breadcrumbs for Navigation**
o	Enable breadcrumbs to see the current file's hierarchy.
o	Click on any breadcrumb to navigate to its corresponding section or parent directory.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
**Finding and Customizing Settings in VS Code**
**Accessing Settings**
**Settings UI**
Via Menu: Go to File > Preferences > Settings (Windows/Linux) or Code > Preferences > Settings (Mac).
Keyboard Shortcut: Press Ctrl+, (Windows/Linux) or Cmd+, (Mac).
**Settings JSON**
Via Settings UI: In the Settings UI, click on the {} icon in the top right corner to open the settings.json file directly.
Via Command Palette: Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac), type Preferences: Open Settings (JSON), and select it.
**Keyboard Shortcuts UI**
Via Menu: Go to File > Preferences > Keyboard Shortcuts (Windows/Linux) or Code > Preferences > Keyboard Shortcuts (Mac).
Keyboard Shortcut: Press Ctrl+K Ctrl+S.

**Changing Settings Examples**
**Changing the Theme**
**Using the Settings UI**
Open the Settings UI.
In the search bar at the top, type theme.
Click on Color Theme.
Select the desired theme from the list.
**Using Command Palette**
Open the Command Palette.
Type Preferences: Color Theme.
Select the desired theme from the list.

**Changing the Font Size**
**Using the Settings UI**
Open the Settings UI.
In the search bar at the top, type font size.
Adjust the Editor: Font Size setting to the desired value.
**Using settings.json**
Open the settings.json file.
Change 14 to your preferred font size.

**Changing Keybindings**
**Using Keyboard Shortcuts UI**
Open the Keyboard Shortcuts UI.
Search for the command you want to rebind (e.g., toggle terminal).
Click the pencil icon next to the command to edit the keybinding.
Press the new key combination you want to assign and hit Enter.
**Using keybindings.json**
Open the Command Palette.
Type Preferences: Open Keyboard Shortcuts (JSON).
Add or modify the keybinding. For example, to change the keybinding for toggling the terminal:
Replace ctrl+ with your preferred key combination.

**Example Customizations**
**Changing the Color Theme to Dark+**
Open the Command Palette.
Type Preferences: Color Theme.
Select Dark+ (default dark) from the list.
**Setting the Font Size to 16**
Open the Settings UI.
Type font size in the search bar.
Set Editor: Font Size to 16.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
**Setting Up and Starting Debugging in VS Code**
**Install VS Code and Node.js**
Download and Install VS Code: VS Code Download
Download and Install Node.js: Node.js Download
**Create a Simple Node.js Program**
Open VS Code.
Create a New Folder for your project and open it in VS Code:
Go to File > Open Folder and select or create a new folder.
Create a New File named app.js:
In the Explorer view, right-click on the folder and select New File. Name it app.js.
Write a Simple Node.js Program:
**Set Up Debugging Configuration**
Open the Run and Debug View:
Click on the Run and Debug icon in the Activity Bar on the side of the window or use the keyboard shortcut Ctrl+Shift+D (Windows/Linux) or Cmd+Shift+D (Mac).
Create a New Debug Configuration:
Click the create a launch.json file link in the Run and Debug view.
Select Node.js from the list of environments.
This creates a launch.json file in a .vscode folder in your project directory.
Configure launch.json:
**Set Breakpoints**
Open app.js.
Click in the gutter to the left of the line numbers where you want to set a breakpoint (e.g., on the line with let result = add(2, 3);).
A red dot will appear, indicating a breakpoint.
**Run the Debugger**- In the Run and Debug view, make sure the configuration you just created is selected.
Click the green play button or press F5 to start debugging.

**Key Debugging Features in VS Code**
**Breakpoints**
Set breakpoints to pause execution at specific lines of code. This allows you to inspect variables, the call stack, and the execution flow.
**Watch**
Add variables to the Watch panel to monitor their values as you step through the code.
**Call Stack**
View the call stack to understand the sequence of function calls that led to the current line of code.
**Variables**
Inspect the values of variables in the Variables panel. This updates as you step through the code.
**Step Through Code**
Use the toolbar buttons or keyboard shortcuts to step through your code:
F10: Step Over
F11: Step Into
Shift+F11: Step Out
F5: Continue
**Debug Console**
Use the Debug Console to evaluate expressions and execute commands in the context of the paused program.
**Inline Values**
o	As you step through your code, VS Code shows the values of variables inline, right next to the code.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
**Integrating Git with VS Code for Version Control**
**Prerequisites**
Install Git- Make sure Git is installed on your system. You can download it from Git's official website.
VS Code- Ensure you have the latest version of Visual Studio Code installed.

**Initializing a Git Repository**
Open VS Code.

Open Your Project Folder
Go to File > Open Folder and select your project folder.

Initialize a Git Repository
Open the Source Control view by clicking the Source Control icon in the Activity Bar on the side of the window or using the keyboard shortcut Ctrl+Shift+G (Windows/Linux) or Cmd+Shift+G (Mac).
Click on Initialize Repository.
VS Code will initialize a new Git repository in your project folder. You’ll see that a .git folder has been created in the root of your project directory.

**Making Commits**
**Stage Changes**- Any changes you make to your files will be shown in the Source Control view.
To stage changes, click the + icon next to each file or click the + icon at the top to stage all changes.
**Commit Changes**- After staging your changes, enter a commit message in the input box at the top of the Source Control view.
Click the checkmark icon or press Ctrl+Enter (Windows/Linux) or Cmd+Enter (Mac) to commit the changes.

**Pushing Changes to GitHub**
**Create a Repository on GitHub**- Go to GitHub and create a new repository. Do not initialize it with a README, .gitignore, or license since you already have a local repository.
**Add the Remote Repository**- Open a terminal within VS Code by pressing Ctrl+ (Windows/Linux) or Cmd+ (Mac).
Add the remote repository URL. Replace <your-repo-url> with the URL of your GitHub repository
**Push Changes to GitHub**- In the terminal, push your changes to GitHub
You might be prompted to log in to GitHub. Provide your GitHub credentials or use an access token if required.

**Using Git Features in VS Code**
**Branching**
Create a new branch by clicking on the current branch name in the status bar at the bottom and selecting Create new branch.
Switch branches by clicking on the branch name and selecting the desired branch.
**Pulling Changes**
To pull changes from the remote repository, click the ellipsis (...) in the Source Control view and select Pull from the dropdown menu, or use the terminal:
**Merging Branches**
Switch to the branch you want to merge into (e.g., master).
Use the terminal to merge another branch
**Resolving Conflicts**
If there are merge conflicts, VS Code will highlight the conflicts in the files.
Use the inline conflict resolution tools provided by VS Code to resolve the conflicts.
After resolving conflicts, stage the changes and commit them.

**Example Workflow**
**Initialize Repository**
Open project in VS Code.
Initialize Git repository in Source Control view.
**Make and Commit Changes**
Edit a file.
Stage the changes.
Enter a commit message and commit.
**Push to GitHub**
Create a repository on GitHub.
Add the remote URL.
Push changes to GitHub.


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

