KELVIN MUSYOKI 
kelvincharlow78@gmail.com
# assignment-1

Developer Environment Setup Guide
Table of Contents
1. Select Your Operating System (OS)
2. Install a Text Editor or Integrated Development Environment (IDE)
3. Set Up Version Control System
4. Install Necessary Programming Languages and Runtimes
5. Install Package Managers
6. Configure a Database (MySQL)
7. Set Up Development Environments and Virtualization 
8. Explore Extensions and Plugins
9. Document Your Setup
10. Reflection

   1. Select Your Operating System (OS)
 Steps to Download and Install Windows 11:

1. Visit the Windows 11 download page.
2. Click on "Download Now" to get the Windows 11 Installation Assistant.
3. Run the Installation Assistant and follow the on-screen instructions to upgrade to Windows 11.

   2. Install a Text Editor or Integrated Development Environment (IDE)
   Steps to Download and Install Visual Studio Code:

1. Visit the Visual Studio Code download page.
2. Select the appropriate installer for your operating system and download it.
3. Run the downloaded installer and follow the on-screen instructions to complete the installation.

   3. Set Up Version Control System
   Steps to Install Git and Configure GitHub:

1. Visit the Git download page and download the installer for your OS.
2. Run the downloaded installer and follow the on-screen instructions to complete the installation.
3. Open a terminal and configure your Git username and email:
      > git config --global user.name "Your Name"
      >git config --global user.email "your-email@example.com"
4. Visit GitHub and sign up for a new account if you don't have one.
5. Create a new repository on GitHub and clone it to your local machine:
      > git clone https://github.com/your-username/your-repository-name.git
6. Open the cloned repository in your text editor and start working on your project.

    4. Install Necessary Programming Languages and Runtimes
    Steps to Install Python:

1. Visit the Python download page and download the latest version for your OS.
2. Run the downloaded installer and ensure you check the box to "Add Python to PATH" during installation.
3. Verify the installation by opening a terminal and running "python --version".

     5. Install Package Managers
     Steps to Install pip for Python:

1. pip is included with Python installations starting from Python 3.4. Verify pip installation
2. If pip is not installed, download get-pip.py from here and run

    6. Configure a Database (MySQL)
    Steps to Install MySQL:

1. Visit the MySQL download page.
2. Download the MySQL Installer and run it.
3. Follow the setup wizard to install MySQL Server and MySQL Workbench.
4. During installation note the root password you set. You will need it to log in to the MySQL server.

    7. Set Up Development Environments and Virtualization
    Steps to Install Docker:

1. Visit the Docker download page and download Docker Desktop for your OS.
2. Run the installer and follow the on-screen instructions.
3. Once installed, open Docker Desktop to ensure it is running correctly.

     8. Explore Extensions and Plugins
     Steps to Install VS Code Extensions:

1. Open VS Code and click on the Extensions icon in the left sidebar.
2. Search for the extension you want to install and click on the "Install" button.
3. Once installed, you can enable the extension by clicking on the "Enable" button.

     9. Document Your Setup
     Steps to Document Your Setup:

1. Create a new file in your project directory called "setup.md".
2. Add a brief description of your project and the steps you took to set it up.
3. Save the file and commit it to your repository.

     10. Reflection.
     
     Issue: Installing MySQL could fail due to missing dependencies.
Solution: Ensure all system updates are installed and retry the installation.

     Issue: Python not being recognized in the terminal.
Solution: Verify that Python is added to the PATH environment variable during installation.
