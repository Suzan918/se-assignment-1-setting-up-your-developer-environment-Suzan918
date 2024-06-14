[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15269318&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   1.Download and Installing Windows 11:
   
   Visit:

   .https://www.microsoft.com/software-download/windows11
   .Click Download Now to get started.
   .Run the Installation Assistant.
   .Accept and Install the licence terms.
   .Click the Restart Now button to complete the installation.
   .Your PC will restart a few times.
   Create Windows 11 Installation Media:

   .Run the Media Creation Tool.
   .Accept the license terms.
   .Select Create installation media for another PC, and then select next.
   .Select which media you want to use: USB flash drive or ISO file.
   .Attach the USB flash drive .
   .Restart your PC.
   .Select the language, time, and keyboard preferences, and then select Next.
   .Select install Windows.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Download VS code:

   .Go to https://code.visualstudio.com/Download
   .Click on the ''Download for Windows''button''

. 
   Install VS code:

   .Run the downloaded installer.
   .Follow the installation prompts.
   .Make sure to check the option ''Add to PATH''for easier access from the command line.
   .Once installed, you can customize VS code with extensions and settings to fit your development needs.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Download Git:

   .Go to the official git website, https://github.com
   .Click on ''Download'' and get the latest version for Windows.
   Install Git:

   .Run the downloaded installer.
   .Follow the installation wizard, using the default settings unless you have specific preferences.
   Configure Git:

   .Open the command prompt or terminal.
   .Open Git bash(Installed with Git)
   Configure your username and email:

   .git config--global user.name''Your Name''
   .git config--global user.email''Your email''
   Create a Github Account:

   .Go to GitHub and sign up for a free account.
   Initialize a Git Repository:

   .Create a new project directory:

     .mkdir my_project
     .cd my_project

   .Initialize a new Git repository:

   .git init
   .Create a README file
   .echo''# My Preject''>>README.md
   .git add README.md
   .git commit -m ''Initial commit''
   
   Create a Repository on GitHub:

   .Go to your GitHub account.
   .Click on ''New'' to create a new repository.
   .Name your repository and follow the prompts.

   Push Local Repository to Github:

   .Add the GitHub repository as a remote.
   .git remote add origin https://github.com/yourusername/my_project.git
   .git branch -M main
   .git push -u origin main

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Installing Python programming language:

  .Go to the Python download page and click on the appropriate link for Windows, https://www.python.org/
  .Download the latest version of Python for Windows.

  Install Python:
  
  .Run the installer.
  .Make sure to check the option ''Add Python to PATh''.
  .Follow the installation prompts.

  Verify Python and pip installation:

  .Open Command Prompt and checkthe versions:
    .python --version
    .pip --version
   
5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Download MySQL:

   .Go to https://dev.mysql.com/downloads/windows/installers/5.7.html
   .Download the MySQL:

   Install MySQL:

   .Run the installer.
   .Follow the prompts to install MySQL Server, MySQL Workbench, and MySQL Shell.

   .Open VS code.
   .Go to Extensions(Ctrl+Shift+X)
   .Search for install the following extensions:
   .Python
   .Gitlens
   .Docker
   .Prettier-Code formatter
   .ESLint

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

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
