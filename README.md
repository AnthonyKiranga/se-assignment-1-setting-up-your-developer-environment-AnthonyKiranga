[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15293870&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   
    Answer
    Prepare Installation Media:

Download winows from the link

Before proceeding, ensure you have backed up any important data on your computer. Installing Windows usually involves formatting the drive, which will erase all existing data.
Access BIOS/UEFI Settings:

Restart your computer and access the BIOS or UEFI firmware settings. This is usually done by pressing a specific key during startup (common keys include F2, F10, F12, Del, Esc, depending on your computer's manufacturer).
Set Boot Order:

In BIOS/UEFI settings, set the boot order to prioritize your installation media (DVD or USB drive) so that the computer boots from it first.
Start the Installation Process:

Save the BIOS/UEFI settings and restart your computer. It should now boot from the installation media.
Follow the on-screen instructions to begin the Windows installation process. You'll need to choose language preferences, time and currency format, and keyboard or input method.
Install Windows:

Click "Install Now" and proceed through the installation wizard.
Enter your product key when prompted. If installing Windows 10, you might be able to skip this step and activate later.
Choose the edition of Windows you want to install (e.g., Home, Pro).
Accept the license terms and choose the type of installation (typically "Custom: Install Windows only (advanced)").
Select the partition where you want to install Windows. If necessary, create new partitions or delete existing ones.
Complete Installation:

Follow the prompts to complete the installation. Your computer may restart several times during this process.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download\

   Answer 
   1.	Open Your Web Browser: Launch your preferred web browser (e.g., Chrome, Firefox, Edge).
2.	Go to Visual Studio Code Download Page: Enter the following URL into your browser's address bar: https://code.visualstudio.com/Download
3.	Select Your Operating System: The download page should automatically detect your operating system (Windows, macOS, or Linux) and display the corresponding download link. If it doesn't, use the dropdown menu to select your OS.
4.	Download the Installer: Click on the download button/link for your operating system. For example:
o	Windows: You'll typically download a .exe installer.
o	macOS: You'll download a .zip archive.
o	Linux: You'll download a .deb (Debian/Ubuntu) or .rpm (Red Hat/Fedora) package, depending on your distribution.
5.	Run the Installer: Once the download is complete:
o	Windows: Double-click the .exe file and follow the installation wizard prompts.
o	macOS: Open the .zip file, then drag and drop the VS Code application into your Applications folder.
o	Linux: Install the .deb or .rpm package using your package manager (dpkg, apt, yum, etc.).
6.	Launch Visual Studio Code: After installation, you can typically find VS Code in your applications menu (Windows and Linux) or launch it from the Applications folder (macOS).
7.	Optional Settings: Once VS Code is launched, you might want to configure some settings according to your preferences. Extensions and additional settings can be managed through the Extensions view (Ctrl+Shift+X).
That's it! You now have Visual Studio Code installed on your system and ready to us



3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Setting up a version control system using Git and GitHub involves a few steps. Here’s a detailed guide to help you through the process:

Step 1: Install Git
Download Git:

Visit the Git website and download the appropriate version for your operating system (Windows, macOS, Linux).
Install Git:

Follow the installation instructions provided by the installer. Ensure that Git is correctly installed by opening a terminal (on macOS or Linux) or Git Bash (on Windows) and typing git --version. This should display the installed Git version.
Step 2: Configure Git
Set Your Username:

Open a terminal (Git Bash on Windows) and set your Git username by typing:
arduino
Copy code
git config --global user.name "Your Name"
Replace "Your Name" with your GitHub username or the name you want to associate with your commits.
Set Your Email:

Set your email address using:
arduino
Copy code
git config --global user.email "your.email@example.com"
Use the email address associated with your GitHub account.
Check Configuration:

You can verify your Git configuration by typing:
css
Copy code
git config --global --list
This will display your configured username and email.
Step 3: Create a GitHub Account
Sign Up on GitHub:
Go to GitHub and sign up for a new account if you haven't already. Follow the instructions to complete the signup process.
Step 4: Create a New Repository on GitHub
Create a New Repository:
Once logged in to GitHub, click on the "+" icon in the top right corner and select "New repository".
Give your repository a name (e.g., my-project), optionally add a description, choose whether it should be public or private, and click on "Create repository".

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Answer

  Download Python:

Go to the official Python website: https://www.python.org/downloads/
Choose the version of Python that you want to install. As of now, Python 3.x is recommended (e.g., Python 3.9 or Python 3.10).
Download the installer appropriate for your operating system (Windows, macOS, or Linux).
Install Python:

Windows:

Run the downloaded installer (.exe file).
Make sure to check the option "Add Python to PATH" during the installation.
Click "Install Now" to start the installation.
macOS:

Open the downloaded package (.pkg file).
Follow the prompts to complete the installation.
Linux:

Python is usually pre-installed on many Linux distributions. You can check by running python3 --version in a terminal.
If Python is not installed or you need a different version, use your package manager (e.g., apt for Debian/Ubuntu or yum for Fedora/Red Hat) to install Python 3 (sudo apt install python3 or sudo yum install python3).
Verify Installation:

After installation, open a terminal or command prompt.
Type python --version or python3 --version to verify that Python is installed correctly and to see the installed version.
Install Necessary Tools (Optional):

Depending on your project requirements, you may need additional tools or packages.
For package management, consider using pip, which is included with Python installations from version 3.4 onwards. You can check its version using pip --version.
IDE or Text Editor (Optional):

For development, you can use any text editor or an integrated development environment (IDE) such as PyCharm, VS Code, or Atom.
IDEs often come with built-in support for Python, including syntax highlighting, code completion, and debugging tools.
By following these steps, you'll have Python installed along with the necessary tools to start programming in Python for your project. Adjustments may be needed based on specific project requirements or operating system configurations.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Answer
   To install pip, the package manager for Python, follow these steps:
1.	Check Python Installation:
o	Before installing pip, ensure that Python is correctly installed on your system. You can verify this by typing python --version or python3 --version in your terminal or command prompt.
2.	Install pip:
o	For Windows:
	If you installed Python using the official installer and checked the option "Add Python to PATH," pip should already be installed. You can verify by opening a command prompt and typing pip --version.
o	For macOS and Linux:
	Open a terminal.
	Use the following command to install pip if it's not already installed:
bash
Copy code
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
	This script downloads get-pip.py and installs pip for Python. If you have multiple versions of Python installed, you might need to use python3 instead of python in the commands above.
3.	Verify pip Installation:
o	After installation, verify pip by typing pip --version in your terminal or command prompt. It should display the version of pip installed.
4.	Updating pip (Optional):
o	It's a good practice to update pip to the latest version:
bash
Copy code
pip install --upgrade pip
5.	Using pip to Install Packages:
o	Once pip is installed, you can use it to install Python packages. For example:
bash
Copy code
pip install package_name
Replace package_name with the name of the package you want to install.
By following these steps, you'll have pip installed and ready to manage Python packages on your system. This is essential for installing and managing dependencies for your Python projects efficiently. Adjustments may be needed based on specific system configurations or requirements.



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
 Answer 
   To configure a MySQL database on a Windows system, you can follow these steps:

Step 1: Download MySQL Installer
Download MySQL Installer:
Visit the MySQL Community Downloads page: MySQL Community Downloads
Download the MySQL Installer for Windows. Choose the appropriate version; typically, you would choose the latest stable version. As of writing, MySQL 8.0 is available, but you can choose 5.7 if needed.
Step 2: Install MySQL Server using MySQL Installer
Run the MySQL Installer:

Once the installer is downloaded, run it by double-clicking the downloaded file (mysql-installer-community-*.exe).
Choose Installation Type:

The MySQL Installer will give you a choice of installation types. For a basic MySQL database setup, choose "Server only" or "Developer Default" depending on your requirements.
Installation Process:

Follow the prompts in the installer. It will guide you through the installation process, including configuring MySQL Server, setting up users, passwords, and other options.
Configure MySQL Server:

During the installation, you will be prompted to configure MySQL Server. Set the root password and other configuration parameters as needed. Make sure to remember the root password as it is essential for managing the MySQL database server.
Complete the Installation:

Once the installation completes successfully, you should have MySQL Server installed on your Windows system.
Step 3: Verify MySQL Installation
Verify Installation:
After installation, you can verify MySQL installation by opening a command prompt and typing mysql -u root -p. Enter the root password you set during installation.
If MySQL is installed correctly, you will see the MySQL command-line client prompt (mysql>).
Step 4: Additional Configuration (Optional)
MySQL Workbench (Optional):

MySQL Workbench is a graphical tool for managing and administering MySQL databases. You can download and install it separately from the MySQL website if you prefer a GUI interface.
Configure Firewall (if needed):

Ensure that your Windows firewall or any other firewall software allows MySQL connections if you plan to access the MySQL server remotely.
Step 5: Start Using MySQL
Create Databases and Tables:
Now that MySQL is installed and running, you can start creating databases, tables, and managing data using SQL commands via the MySQL command-line client or MySQL Workbench.
By following these steps, you should be able to successfully download, install, and configure MySQL database on your Windows system. Adjust the installation options based on your specific requirements and preferences.





7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Answer
Using Docker for Development
1.	Install Docker:
o	Docker provides containers that encapsulate your application and its dependencies, ensuring consistency across different environments.
o	Install Docker Desktop from Docker's official website.
2.	Create a Dockerfile:
o	A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image. This file serves as the blueprint for your Docker image.
o	Example Dockerfile for a Node.js application:
dockerfile
Copy code
FROM node:14

# Set working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy application code
COPY . .

# Expose the port
EXPOSE 3000

# Command to run the application
CMD ["npm", "start"]
3.	Build Docker Image:
o	Navigate to the directory containing your Dockerfile and build the Docker image:
perl
Copy code
docker build -t my-node-app .
4.	Run Docker Container:
o	Once the image is built, you can run a container based on this image:
arduino
Copy code
docker run -p 3000:3000 my-node-app
o	This command maps port 3000 on your local machine to port 3000 inside the Docker container where your Node.js application is running.
5.	Managing Dependencies:
o	Docker ensures that all dependencies (including OS-level dependencies) are consistent across different environments.
Using Virtual Machines for Development
1.	Install Virtualization Software:
o	Examples include VirtualBox, VMware, or Hyper-V.
o	Install the software suitable for your operating system.
2.	Create a Virtual Machine:
o	Use the virtualization software to create a new virtual machine (VM).
o	Allocate appropriate resources (CPU, RAM, disk space) based on your project requirements.
3.	Install Guest OS:
o	Install the operating system (e.g., Ubuntu, CentOS) within the VM.
4.	Setup Development Environment:
o	Install necessary tools, libraries, and dependencies within the VM.
5.	Snapshot and Cloning:
o	Take snapshots of your VM once you have configured it properly. This allows you to revert to a known state if needed.
o	Clone VMs to replicate development environments across different machines.
Benefits of Using Virtualization Tools
•	Isolation: Each project or application can have its own isolated environment, preventing conflicts between dependencies.
•	Consistency: Ensure that your development environment matches the production environment closely.
•	Portability: Easily share development environments with team members or deploy them to cloud services.
By setting up development environments using Docker or virtual machines, you can enhance collaboration, minimize configuration issues, and streamline your development workflow. Choose the option that best fits your project requirements and team dynamics.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   Answer
   Visual Studio Code (VS Code)
VS Code has a vast ecosystem of extensions available through its marketplace:

ESLint: Provides linting for JavaScript and TypeScript.
Prettier - Code formatter: Code formatting for various languages.
GitLens: Enhances Git integration with powerful history and repository visualization tools.
Live Share: Collaborative editing and debugging in real-time.
Docker: Adds syntax highlighting, snippets, and Dockerfile support.
Jupyter: Interactive computing with Jupyter Notebooks.
Bracket Pair Colorizer: Matches brackets with colors to improve code readability.
Path Intellisense: Autocompletes filenames.
Debugger for Chrome: Debug JavaScript in the Chrome browser.
Python: Official extension for Python development.
Sublime Text
Sublime Text uses packages for extending functionality:

Sublime Linter: Provides framework for linting code.
Package Control: Manages packages (similar to extensions in VS Code).
Emmet: Speeds up HTML & CSS workflow with shortcuts.
Git: Adds Git integration for version control.
BracketHighlighter: Provides customizable bracket highlighting.
AutoFileName: Autocompletes filenames in the editor.
JavaScriptNext: Enhances JavaScript syntax highlighting.
Alignment: Aligns multi-line and multiple selections.
IntelliJ IDEA (and JetBrains IDEs)
JetBrains IDEs have plugins available through their plugin repositories:

SonarLint: Analyzes code quality on-the-fly.
Markdown Support: Provides syntax highlighting and preview for Markdown files.
CheckStyle-IDEA: Integrates CheckStyle for Java code style checking.
Database Tools and SQL: Adds SQL support directly within the IDE.
JUnit: Framework for running and debugging Java tests.
Spring Assistant: Adds support for Spring Framework.
Docker Integration: Manages Docker containers from within the IDE.
Key Promoter X: Helps learn keyboard shortcuts by showing tooltips.
Atom
Atom editor has a package system for extending its features:

Atom IDE: Adds support for language services (JavaScript, TypeScript, etc.).
Minimap: Provides a preview of the full source code.
File Icons: Adds file icons to the tree view.
Atom Beautify: Formats code in various languages.
PlatformIO IDE Terminal: Integrated terminal within the editor.
Git Plus: Adds Git commands and utilities.
Linter: Framework for providing linting.
Emmet: Expands abbreviations into HTML or CSS.
Emacs
Emacs uses packages and modes to extend functionality:

Magit: Git interface within Emacs.
Flycheck: On-the-fly syntax checking.
YASnippet: Template system for Emacs.
Company: Autocompletion framework.
Projectile: Project interaction library.
Org mode: Mode for organizing notes, tasks, and projects.
Elpy: Emacs Python Development Environment.
Markdown mode: Major mode for editing Markdown files.
Vim (and Neovim)
Vim uses plugins for extending its capabilities:

NERDTree: File system explorer.
YouCompleteMe: Autocompletion engine.
CtrlP: Fuzzy file finder.
Vim-airline: Status/tabline for Vim.
Syntastic: Syntax checking.
Vim-fugitive: Git integration.
UltiSnips: Snippet engine for Vim.
Vimtex: Vim plugin for LaTeX.
Other Editors
Other editors like Emacs, Sublime Text, Atom, and more also have vibrant ecosystems with plugins and extensions tailored to enhance specific workflows.

Conclusion
Choosing the right extensions depends on your programming language, workflow preferences, and specific needs (like Git integration or advanced debugging). Exploring these extensions can greatly improve productivity and coding experience in your preferred editor or IDE.
   

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
