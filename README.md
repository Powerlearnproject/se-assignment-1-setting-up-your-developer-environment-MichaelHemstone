[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15275866&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

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

THE ANSWERS

TASK 1

Requirements:
Check Compatibility:

Ensure your PC meets the minimum requirements for Windows 11. This includes CPU compatibility (like TPM 2.0 and Secure Boot capable), RAM, and storage space.
You can use Microsoft's PC Health Check tool to verify compatibility.
Backup Your Data:

Before proceeding with any major operating system installation, it's wise to back up your important files to avoid losing data.
Installation Steps:
Get Windows 11 Installation Media:

Go to the Windows 11 download page on Microsoft's website.
Click on "Download now" to download the Windows 11 Installation Assistant.
Create Installation Media:

Once downloaded, run the Windows 11 Installation Assistant.
Follow the on-screen instructions to create a bootable USB drive or download an ISO file.
Install Windows 11:

Insert the bootable USB drive or mount the ISO file (if you downloaded it).
Restart your computer and boot from the USB drive or ISO.
Follow the prompts to begin installing Windows 11.
Choose your preferences and settings during the installation process.
Complete Setup:

After installation completes, you’ll need to set up Windows 11 by creating user accounts and configuring initial settings.
Install Drivers and Updates:

Once Windows 11 is installed, it’s a good idea to install the latest drivers for your hardware and perform Windows Updates to ensure your system is up to date.
Activation:
Activate Windows 11 using your product key if required. If your PC came with Windows 10 and meets the requirements, it may activate automatically.

TASK 2
Steps to Download and Install Visual Studio Code:
Download Visual Studio Code:

Go to the Visual Studio Code website.
Click on the "Download for [Your Operating System]" button. VS Code supports Windows, macOS, and Linux.
Install Visual Studio Code:

Windows:

Once the download completes, run the installer (.exe file).
Follow the prompts in the Setup Wizard. You can choose the default options unless you want to customize the installation directory or other settings.
After installation, you can launch Visual Studio Code from the Start menu or desktop shortcut.
macOS:

Open the downloaded .dmg file.
Drag and drop the Visual Studio Code app into the Applications folder.
Launch Visual Studio Code from the Applications folder, Spotlight, or by using the terminal command code.
Linux (Debian/Ubuntu example):

Download the .deb package.
Open a terminal and navigate to the directory where the .deb package is downloaded.
Run sudo dpkg -i <package-file-name>.deb to install the package.
If there are any dependencies issues, run sudo apt-get install -f.
Launch Visual Studio Code by typing code in the terminal.
Initial Setup:

When you first launch Visual Studio Code, it will prompt you to install recommended extensions based on the programming languages it detects.
You can also customize settings (accessible via File > Preferences on Windows/Linux or Code > Preferences on macOS).
Install Extensions:

Visual Studio Code’s power comes from its extensions. You can install extensions for different programming languages, themes, and additional tools.
Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side (or use Ctrl+Shift+X shortcut).
Search for extensions, click install, and follow any prompts.
Customize and Start Coding:

Customize VS Code further through settings (File > Preferences > Settings or Code > Preferences > Settings).
Start coding by opening a folder or file, and enjoy the rich features and performance of Visual Studio Code!
Additional Notes:
Visual Studio Code is continuously updated with new features and improvements. Check for updates regularly (Help > Check for Updates).
Explore the vast range of extensions available to tailor VS Code to your specific needs and programming languages.

TASK 3
Installing Git:
Download Git:

Visit the Git website.
Download the installer suitable for your operating system (Windows, macOS, Linux).
Install Git:

Windows:

Run the downloaded .exe file.
Follow the installation wizard instructions. You can usually choose the default options.
macOS:

Run the downloaded .dmg file.
Follow the prompts in the installer.
After installation, Git should be accessible from the Terminal.
Linux:

Use your package manager to install Git. For example, on Debian/Ubuntu:
sql
Copy code
sudo apt-get update
sudo apt-get install git
On CentOS/Fedora:
Copy code
sudo yum install git
On Arch Linux:
Copy code
sudo pacman -S git
Verify Installation:

Open a terminal (or Git Bash on Windows) and type:
css
Copy code
git --version
This should display the installed Git version. If not, ensure Git is correctly added to your system's PATH.
Configuring Git:
Configure Git with Your Information:
Open a terminal (or Git Bash on Windows).
Set your username and email (used for commit messages):
arduino
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Replace "Your Name" and "your.email@example.com" with your actual name and email address.
Creating a GitHub Account:
Create a GitHub Account:
Visit GitHub and sign up for a new account if you haven't already.
Initializing a Git Repository and Making Your First Commit:
Create a New Project Directory:

Choose or create a directory for your project on your local machine.
Initialize Git Repository:

Open a terminal (or Git Bash on Windows) and navigate to your project directory:
bash
Copy code
cd /path/to/your/project
Initialize a new Git repository:
csharp
Copy code
git init
This initializes a new Git repository in your project directory.
Create Your Project Files:

Add your project files into this directory.
Add Files to the Staging Area:

Add your files to the staging area (ready for commit):
csharp
Copy code
git add .
The . adds all files. You can specify individual files (git add filename) if needed.
Commit Your Changes:

Commit the staged files with a commit message:
sql
Copy code
git commit -m "Initial commit"
Replace "Initial commit" with a meaningful commit message describing your changes.
Connect Your Local Repository to GitHub:

Create a new repository on GitHub.
Follow the instructions shown on GitHub when you create a new repository. It usually involves adding a remote repository:
csharp
Copy code
git remote add origin https://github.com/your-username/repository-name.git
Replace your-username with your GitHub username and repository-name with the name of your repository on GitHub.
Push Your Commits to GitHub:

Push your changes to GitHub:
css
Copy code
git push -u origin main
This pushes your commits to the main branch (or master branch if you haven't changed the default) on GitHub.

TASK 4
Installing Python:
Download Python:

Visit the Python downloads page.
Download the latest version of Python suitable for your operating system (Windows, macOS, or Linux).
Install Python:

Windows:

Run the downloaded .exe file.
Ensure to check the box "Add Python to PATH" during the installation wizard.
Click "Install Now" and follow the prompts.
macOS:

Run the downloaded .pkg file.
Follow the prompts in the installer.
Linux:

Python is often pre-installed on many Linux distributions. However, to install the latest version or manage Python versions, use your package manager:
On Debian/Ubuntu:
sql
Copy code
sudo apt update
sudo apt install python3
On CentOS/Fedora:
Copy code
sudo yum install python3
On Arch Linux:
Copy code
sudo pacman -S python
Verify Installation:

Open a terminal (or command prompt on Windows) and check the Python version:
css
Copy code
python --version
This should display the installed Python version. Use python3 instead of python on some systems where Python 2.x is still the default.
Installing Python Packages:
Using pip (Python Package Installer):
Python comes with pip (Python package installer) by default.

Upgrade pip (recommended):

css
Copy code
python -m pip install --upgrade pip
Install packages:

You can install packages using pip. For example:
Copy code
pip install package_name
Setting Up Python Environment:
IDE or Text Editor:
You can use Visual Studio Code (which we installed earlier) or any other preferred IDE/text editor for coding in Python.
Testing Your Python Installation:
Create and Run a Python Script:

Create a simple Python script (e.g., hello.py) using your IDE or a text editor:
python
Copy code
print("Hello, Python!")
Save the file.
Execute the Python Script:

Open a terminal or command prompt.
Navigate to the directory where hello.py is saved.
Run the script:
Copy code
python hello.py
You should see Hello, Python! printed to the console.
Additional Tools:
Python Virtual Environments (optional but recommended):
Virtual environments help manage dependencies and isolate project environments.
Create a virtual environment:
Copy code
python -m venv myenv
Activate the virtual environment:
Windows:
Copy code
myenv\Scripts\activate
macOS/Linux:
bash
Copy code
source myenv/bin/activate
Install packages within the virtual environment using pip.

TASK 5
Checking pip Installation:
Verify pip Installation:
Open a terminal or command prompt.
Type the following command to check the pip version:
css
Copy code
pip --version
If pip is installed, you should see the version number. If it's not installed or you get an error, you can proceed with the installation or upgrade steps below.
Installing or Upgrading pip:
Install or Upgrade pip (if needed):
To install pip (if it's missing):

Download get-pip.py script from https://bootstrap.pypa.io/get-pip.py.
Open a terminal or command prompt and navigate to the directory where get-pip.py is downloaded.
Run the following command:
arduino
Copy code
python get-pip.py
This will install pip for your Python installation.
To upgrade pip to the latest version:

css
Copy code
python -m pip install --upgrade pip
Using pip:
Installing Python Packages:
Once pip is installed or upgraded, you can use it to install Python packages. For example:

Copy code
pip install package_name
Replace package_name with the name of the package you want to install.

To install a specific version of a package:

Copy code
pip install package_name==1.2.3
To install packages from a requirements file (requirements.txt):

Copy code
pip install -r requirements.txt
To list installed packages:

Copy code
pip list
Updating pip:
Periodically Update pip:
It's good practice to keep pip updated to the latest version to ensure compatibility and security fixes:
css
Copy code
python -m pip install --upgrade pip
Troubleshooting:
Proxy Configuration:
If you're behind a corporate proxy, you may need to configure pip to use it. This can be done by setting environment variables (HTTP_PROXY, HTTPS_PROXY, NO_PROXY).

TASK 6
Installing MySQL:
Run the Installer:

Windows:

Double-click the downloaded .msi file to start the installation.
Follow the installation wizard prompts.
Choose "Developer Default" or "Server Only" as per your requirement. Developer Default includes MySQL Server and other development tools.
macOS:

Open the downloaded .dmg file.
Drag the MySQL installer package to the Applications folder.
Open the package in the Applications folder to start the installation.
Follow the prompts in the installer.
Linux:

MySQL installation on Linux varies by distribution. It's often available through the package manager.
For Debian/Ubuntu, you can install MySQL using:
sql
Copy code
sudo apt-get update
sudo apt-get install mysql-server
For CentOS/Fedora, use:
Copy code
sudo yum install mysql-server
Follow the prompts to complete the installation.
Configuration:

During installation on Windows and macOS, you may be prompted to set a root password for MySQL. Choose a strong password and remember it.
On Linux, the root password setup might occur post-installation. Follow the instructions in the terminal.
Start MySQL Server:

Windows:

MySQL Server usually starts automatically after installation.
To start or stop MySQL manually, use services.msc or MySQL Installer console.
macOS:

MySQL Server starts automatically after installation.
To start or stop MySQL manually:
sql
Copy code
sudo /usr/local/mysql/support-files/mysql.server start
sudo /usr/local/mysql/support-files/mysql.server stop
Linux:

MySQL service starts automatically after installation on most distributions.
Use commands like systemctl to start, stop, and check the status of the MySQL service.
Verifying MySQL Installation:
Verify MySQL Installation:
Open a terminal or command prompt and connect to MySQL using the root account and password you set during installation:
css
Copy code
mysql -u root -p
If successful, you'll see the MySQL command-line prompt (mysql>).
Additional Steps (Optional):
MySQL Workbench (Optional):

MySQL Workbench is a visual tool to manage MySQL databases.
Download and install MySQL Workbench from the MySQL Workbench Downloads page.
Configuring MySQL:

Configure MySQL server settings as per your requirements, such as network access, users, and database settings.

TASK 7
Using virtualization tools like Docker or virtual machines is indeed a great approach to isolate project dependencies and ensure consistent environments across different machines. Here’s how you can leverage Docker specifically to manage project dependencies:

Using Docker for Isolating Project Dependencies:
Install Docker:

Windows:

Download and install Docker Desktop from the Docker Desktop for Windows page.
Follow the installation wizard instructions to set up Docker on your machine.
macOS:

Download and install Docker Desktop for Mac from the Docker Desktop for Mac page.
Follow the installation instructions provided.
Linux:

Docker installation on Linux varies by distribution. Refer to the official Docker documentation for Install Docker Engine on Linux for detailed instructions specific to your distribution.
Verify Docker Installation:

Open a terminal (or Docker Quickstart Terminal on Windows/macOS).
Check Docker version to verify installation:
css
Copy code
docker --version
Using Docker for Projects:

Dockerfile:

Create a Dockerfile in your project directory to define the environment setup.
Example Dockerfile for a Python project:
dockerfile
Copy code
# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME World

# Run app.py when the container launches
CMD ["python", "app.py"]
Build Docker Image:

Build the Docker image from the Dockerfile:
perl
Copy code
docker build -t my-python-app .
Run Docker Container:

Start a Docker container from the built image:
arduino
Copy code
docker run -p 4000:80 my-python-app
This command maps port 80 inside the container to port 4000 on your host machine.
Manage Dependencies:

Docker ensures that all dependencies specified in the Dockerfile (like Python packages in requirements.txt) are consistent across different environments.
Advantages of Using Docker:
Isolation: Docker containers encapsulate dependencies and configurations, ensuring consistency and reproducibility across different environments.

Portability: Containers can be easily moved between different machines or cloud platforms, ensuring your application behaves the same everywhere.

Version Control: Docker images can be versioned and stored in registries (like Docker Hub), facilitating collaboration and deployment.

TASK 8
Enhancing your text editor or IDE with extensions, plugins, and add-ons can significantly improve productivity and development experience. Here are some essential categories of extensions to consider for popular text editors and IDEs like Visual Studio Code:

Essential Categories of Extensions:
Syntax Highlighting and Language Support:

Extensions that provide syntax highlighting and language support for various programming languages beyond the defaults.
Linting and Code Analysis:

Plugins that integrate linting tools (like ESLint, Pylint) to catch errors, enforce coding standards, and improve code quality.
Code Formatting:

Plugins to automatically format code according to style guidelines (e.g., Prettier, Black) for consistent code formatting.
Version Control Integration:

Extensions to integrate with version control systems like Git for seamless source code management directly from your editor.
Debugging Tools:

Extensions that provide debugging capabilities for different programming languages, allowing you to debug code directly within your editor.
IntelliSense and Autocompletion:

Plugins that enhance code completion (IntelliSense) by providing intelligent suggestions and auto-completion of code snippets.
Project Management:

Tools to manage and navigate through large codebases efficiently, including file search, workspace management, and project visualization.
Examples of Extensions for Visual Studio Code:
Syntax Highlighting and Language Support:

Language Support: Provides support for specific languages beyond the defaults.
Linting and Code Analysis:

ESLint: Integrates ESLint for JavaScript/TypeScript.
Pylint: Provides linting for Python code.
Code Formatting:

Prettier: Automatically formats code according to predefined rules.
Version Control Integration:

GitLens: Enhances Git integration with features like annotations, blame information, and more.
Debugging Tools:

Debugger for Chrome: Allows debugging JavaScript code in Google Chrome directly from VS Code.
IntelliSense and Autocompletion:

Python Extension: Provides rich support for Python, including IntelliSense, debugging, and code snippets.
Project Management:

Project Manager: Helps manage projects with shortcuts to switch between projects and folders.
How to Install Extensions in Visual Studio Code:
Open Extensions View:

Click on the Extensions icon in the Activity Bar on the side of VS Code (or use Ctrl+Shift+X shortcut).
Search and Install Extensions:

Search for extensions by name (e.g., "ESLint", "Prettier") in the Extensions Marketplace.
Click on the extension you want to install and then click "Install".
Manage Installed Extensions:

Manage installed extensions from the Extensions view, where you can enable/disable, update, or uninstall extensions as needed.







