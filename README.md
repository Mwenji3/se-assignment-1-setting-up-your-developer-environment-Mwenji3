[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15351796&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Step 1: Download and Install Windows 11
Go to the Windows 11 download page.
Click on "Download now" to get the Windows 11 Installation Assistant.
Run the installer and follow the on-screen instructions to upgrade your OS to Windows 11.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Step 2: Download and Install Visual Studio Code
Go to the Visual Studio Code download page.
Click on the "Download for Windows" button.
Run the downloaded installer (VSCodeSetup-x.y.z.exe).
Follow the installation steps and select options like creating a desktop icon and adding VS Code to the PATH environment variable.
Complete the installation by clicking "Finish."

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com


Step 3.1: Install Git
Download Git from the official Git website.
Run the installer and follow the default settings unless you have specific preferences.
Ensure the option "Git Bash Here" is checked during the installation.
Step 3.2: Create a GitHub Account
Go to GitHub and sign up for a new account if you don't have one.
Verify your email address to activate your account.
Step 3.3: Initialize a Git Repository
Open VS Code and create a new folder for your project.
Open the folder in VS Code.
Open the integrated terminal (Ctrl+).
Run the following commands to initialize a Git repository:

git init
git add .
git commit -m "Initial commit"
Create a new repository on GitHub and follow the instructions to push your local repository to GitHub:

git remote add origin https://github.com/yourusername/your-repo-name.git
git branch -M main
git push -u origin main

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.


Step 4: Install Python
Go to the Python download page.
Click on "Download Python" and choose the latest stable release.
Run the installer and ensure the option "Add Python to PATH" is checked.
Follow the installation steps and complete the setup.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).


Step 5: Install pip
pip should be installed automatically with Python. You can verify this by running:

pip --version


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html


Step 6: Download and Install MySQL
Go to the MySQL download page.
Download the MySQL Installer and run it.
Select the "Developer Default" setup type.
Follow the on-screen instructions to complete the installation, including setting up a root password and configuring MySQL as a Windows service.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.


Go to the Docker download page and download Docker Desktop for Windows.
Run the installer and follow the instructions to complete the setup.
Start Docker Desktop and ensure it is running correctly.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.


Install Essential VS Code Extensions
Open VS Code and go to the Extensions view (Ctrl+Shift+X).
Search for and install the following extensions:
Prettier: Code formatter
ESLint: Linting for JavaScript/TypeScript
Python: Support for Python development
Live Server: Live preview of web pages
Docker: Integration with Docker

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


 Create a Setup Documentation
Create a comprehensive document outlining the steps you've taken to set up your developer environment.
Include screenshots where necessary to illustrate each step.
Document any configurations, customizations, or troubleshooting steps encountered during the process.


#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).

https://github.com/Mwenji3/GitSessionPLP.git

- A reflection on the challenges faced during setup and strategies employed to overcome them.


Challenges and Solutions:
Challenge: Understanding how to configure environment variables in Windows.
Solution: Followed detailed guides and verified configurations using command prompts.
Challenge: Ensuring all tools work seamlessly together (e.g., Python, VS Code, Git).
Solution: Tested each tool individually and referred to community forums for troubleshooting.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
