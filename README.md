[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15272401&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Download the Windows 11 ISO file from the Microsoft website.
Create a bootable USB drive using tools like Rufus or the Windows Media Creation Tool.
Boot from Installation Media:
Insert the bootable USB drive into your computer.
Restart the computer and enter the BIOS/UEFI settings (usually by pressing a key like F2, F12, Del, or Esc during startup).
Set the USB drive as the primary boot device and save changes.
Start Windows Setup:
Boot from the USB drive and start the Windows Setup.
Select your language, time, and keyboard preferences, then click "Next."
Install Now:
Click "Install Now" on the Windows Setup screen.
Enter Product Key:
Enter your Windows 11 product key. If you don’t have one, select "I don’t have a product key."
Accept License Terms:
Read and accept the Microsoft Software License Terms, then click "Next."
Select Installation Type:
Choose "Custom: Install Windows only (advanced)" for a clean installation.
Partition the Drive:
Select the drive where you want to install Windows 11. You can create, delete, or format partitions as needed, then click "Next."
Install Windows:
The installation process will begin, and the system will copy files, install features and updates, and complete the installation. This may take some time, and the computer will restart several times.
Set Up Windows:
After installation, you’ll need to go through the initial setup process:
Select your country/region, language, and keyboard layout.
Connect to a network and sign in with your Microsoft account or create a local account.
Configure privacy settings and other preferences.
Complete Setup:
Once the setup is complete, you’ll be taken to the Windows 11 desktop, where you can start using your new operating system.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Run the Installer:
Locate the downloaded file (usually in your Downloads folder) and double-click VSCodeSetup.exe to run the installer.
Setup Installation:
License Agreement: Read and accept the license agreement by checking the box and clicking "Next."
Destination Folder: Choose the installation destination folder or leave it as default and click "Next."
Select Additional Tasks:
Check "Create a desktop icon" if you want a shortcut on your desktop.
Optionally, you can check the following:
"Add to PATH" (recommended for command line usage).
"Register Code as an editor for supported file types."
"Add 'Open with Code' action to Windows Explorer file context menu."
"Add 'Open with Code' action to Windows Explorer directory context menu."
Click "Next" after making your selections.
Install:
Click the "Install" button to begin the installation process.
Launch Visual Studio Code:
Once the installation is complete, check "Launch Visual Studio Code" and click "Finish."
Post-Installation Key Steps
Initial Setup:
On first launch, you may be greeted with a welcome screen providing options for customization, tutorials, and setting up version control.
Install Extensions:
Click on the Extensions icon on the sidebar or press Ctrl+Shift+X.
Search for and install extensions such as:
Python: For Python development.
Prettier: Code formatter.
ESLint: Linting for JavaScript/TypeScript.
Any other language or tool-specific extensions you need.
Configure Settings:
Open the settings by clicking on the gear icon at the bottom left corner and selecting "Settings," or press Ctrl+,.
Customize your settings, such as theme, font size, editor behavior, etc.
Set Up Git Integration:
If you use Git for version control, configure it by opening the Source Control view and following prompts to set up a repository.
You might need to install Git if it’s not already installed on your system.
Command Palette:
Access the Command Palette by pressing Ctrl+Shift+P. This is a powerful tool to execute commands, install extensions, and configure settings.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

1.Run the Installer:
Locate the downloaded file (usually in your Downloads folder) and double-click Git-*.exe to run the installer.
2.Setup Installation:
License Agreement: Read and accept the license agreement by clicking "Next."
Select Destination Location: Choose the installation destination folder or leave it as default and click "Next."
Select Components: Choose components you want to install (default selections are usually sufficient) and click "Next."
Select Start Menu Folder: Choose a start menu folder or leave it as default and click "Next."
Adjusting Your PATH Environment:
Choose the recommended option "Git from the command line and also from 3rd-party software" and click "Next."
Choosing the SSH executable:
Choose "Use the OpenSSH" option and click "Next."
Choosing HTTPS transport backend:
Choose "Use the OpenSSL library" and click "Next."
Configuring the line ending conversions:
Choose "Checkout Windows-style, commit Unix-style line endings" and click "Next."
Configuring the terminal emulator to use with Git Bash:
Choose "Use MinTTY (the default terminal of MSYS2)" and click "Next."
Choosing the default Git pull behavior:
Choose "Default (fast-forward or merge)" and click "Next."
Choose a credential helper:
Choose "Git Credential Manager" and click "Next."
Configuring extra options:
Leave the default options checked and click "Next."
Configuring experimental options:
Uncheck experimental options unless you want to try them and click "Install."
3.Complete Installation:
Wait for the installation to complete and click "Finish."
Key Configuration Steps
1.Open Git Bash:
Open Git Bash from the Start Menu or by right-clicking on the desktop and selecting "Git Bash Here."
2.Set Up User Information:
Configure your username and email address, which will be used for commits.
sh
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
3 Verify Installation:
Verify that Git is installed and configured correctly.
sh
Copy code
git --version
git config --global --list
4.Set Up SSH Key (Optional but Recommended):
Generate an SSH key if you plan to use SSH for GitHub or other Git servers.
sh
Copy code
ssh-keygen -t rsa -b 4096 -C "ngwazi97@97gmail.com"

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  
Run the Installer:
Locate the downloaded file (usually in your Downloads folder) and double-click python-<version>.exe to run the installer.
Setup Installation:
Add Python to PATH:
At the bottom of the installer window, check the box that says "Add Python <version> to PATH."
Choose Installation Type:
Click on "Customize installation" for more options or "Install Now" for the default installation.
Optional Features (Customize installation):
Ensure that "pip" (Python package manager) is checked.
Optionally, check other features like "IDLE," "Documentation," and "tcl/tk and IDLE" for GUI support.
Click "Next" after selecting the desired optional features.
Advanced Options:
Check "Install for all users" if required.
Optionally, customize the installation location or leave it as default.
Ensure "Precompile standard library" is checked for faster performance.
Click "Install" to start the installation.
Complete Installation:
Wait for the installation process to complete.
Click "Close" once the installation is finished.
Post-Installation Key Steps
Verify Installation:
Open Command Prompt (you can search for cmd in the Start menu).
Type python --version and press Enter to verify the installation. You should see the installed Python version.
Type pip --version to verify that pip (Python package manager) is installed correctly.
Install Virtual Environment:
To create isolated environments for your projects, install virtualenv:
sh
Copy code
pip install virtualenv
Configure Environment Variables (if needed):
Although the installer should have added Python to your PATH, you can verify or manually add it:
Open the Start menu, search for "Environment Variables," and select "Edit the system environment variables."
In the System Properties window, click "Environment Variables."
In the Environment Variables window, find the "Path" variable in the "System variables" section and ensure that the paths to your Python installation (C:\Python<version>\) and the Scripts folder (C:\Python<version>\Scripts\) are listed.
Install Common Packages:
Use pip to install commonly used packages:
sh
Copy code
pip install numpy pandas matplotlib
Set Up IDE/Code Editor:
Use an IDE or code editor like Visual Studio Code, PyCharm, or any other editor that supports Python development.
Configure the IDE to use the installed Python interpreter. In Visual Studio Code, you can do this by:
Opening the Command Palette (Ctrl+Shift+P).
Searching for "Python: Select Interpreter" and choosing the installed Python version.
5.Install Package Managers:
If applicable, install package managers like pip (Python).
6.Configure a Database (MySQL):
Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Step 1: Download MySQL Installer
Go to MySQL Download Page: Visit the MySQL Community Downloads page.
Select MySQL Community Server: Choose the appropriate MySQL Community Server version based on your operating system. Click on the "Download" button.
Step 2: Run the MySQL Installer
Launch the Installer: Once the installer file (.exe on Windows, .dmg on macOS, .tar.gz on Linux) is downloaded, double-click to launch it.
Select Setup Type: Choose the setup type. For most users, "Developer Default" or "Server only" is recommended for a typical installation. Click "Next".
Installation Process: Follow the prompts to install MySQL. You may need to accept a license agreement and choose the installation directory.
Step 3: Configure MySQL Server
Configuration: During installation, you will be prompted to configure MySQL Server.
Set up MySQL root password: Choose a secure password for the MySQL root user (administrator).
Port configuration: By default, MySQL uses port 3306. You can change this if necessary.
Start MySQL Server at system startup: Choose whether MySQL should start automatically when your computer starts.
Complete Installation: Finish the installation process. The installer will finalize the setup and configure MySQL Server with the options you selected.
Step 4: Verify Installation
Check MySQL Installation:
Open a command prompt (Windows) or terminal (macOS/Linux).
Type mysql -V or mysql --version to check if MySQL is installed and the version installed.
Step 5: (Optional) Install MySQL Workbench (GUI Tool)
Download MySQL Workbench: If you prefer a graphical interface to manage MySQL, download MySQL Workbench from the same MySQL Download page.
Install MySQL Workbench: Run the installer for MySQL Workbench and follow the installation instructions.
Step 6: Start Using MySQL
Connect to MySQL Server: Use MySQL Command-Line Client or MySQL Workbench to connect to the MySQL server using the root account and the password you set during installation.
Create Databases and Tables: Begin creating databases, tables, and managing data in MySQL as needed.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Using virtualization tools like Docker or virtual machines is highly beneficial for isolating project dependencies and ensuring consistent environments across different machines. Here’s a summary of the advantages and considerations:

Advantages:
Dependency Isolation: Docker containers and virtual machines encapsulate all dependencies (libraries, frameworks, tools) needed for a project. This isolation prevents conflicts and ensures that each project runs in its own environment.
Consistency: By packaging the entire environment (including OS libraries and configurations), you can ensure that the application behaves consistently across different development machines, staging servers, and production environments.
Portability: Docker containers, especially, are lightweight and portable. Once you define a Dockerfile (for Docker) or a virtual machine image, you can easily share it with team members or deploy it to cloud services without worrying about compatibility issues.
Reproducibility: With Docker images or virtual machine snapshots, you can recreate the exact same environment whenever needed. This is crucial for debugging, testing, and deploying applications reliably.
Resource Efficiency: Virtualization technologies often allow for efficient resource utilization by sharing resources among containers or virtual machines on a single host.

Considerations:
Learning Curve: Docker and virtual machines may have a learning curve, especially for those new to virtualization concepts and tools.
Performance Overhead: Running applications within containers or virtual machines incurs some overhead due to virtualization. However, this overhead is often minimal for most applications.
Maintenance: Docker containers and virtual machines require regular updates and maintenance of their images and configurations to ensure security and compatibility with newer versions of dependencies.
Tooling Ecosystem: Choosing the right virtualization tool and managing containers or virtual machines effectively might require familiarity with additional tooling (e.g., Docker Compose, Kubernetes for Docker).

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

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
