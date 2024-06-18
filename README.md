[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15237639&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

<ol>
   <li><h2>Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11</h2></li>
   <h3>Windows Installation</h3>
   <ol>
      <li><li>Go to the <a href = "https://www.microsoft.com/software-download/windows11">Microsoft Windows 11 download page<a/></li>
      <li><li>Go to the <a href = "https://www.microsoft.com/en-us/software-download/windows10ISO">Microsoft Windows ISO<a/></li>
   </ol>
   <h3>What you need</h3>
      <ol>
         <li>Windows installation media. This could be an installation ISO or DVD.</li>
         <li>USB flash drive with at least 5GB free space,ensure the flash disk has nothing important since it will be formatted.</li>
         <li>Technician PC - Windows PC that you'll use to format the USB flash drive</li>
         <li>Destination PC - A PC that you'll install Windows on</li>
      </ol>
   <h3>Steps</h3>
   </ol>
      <li>Format the drive and set the primary partition as active.</li>
      <ul>
         <li>Connect the USB flash drive to your technician PC.</li>
         <li>Open Disk Management: Right-click on Start and choose Disk Management.</li>
         <li>Format the partition: Right-click the USB drive partition and choose Format. Select the FAT32 file system to be able to boot either BIOS-based or UEFI-based PCs.</li>
         <li>Set the partition as active: Right-click the USB drive partition and click Mark Partition as Active.</li>
      </ul>
      <li>Copy Windows Setup to the USB flash drive.</li>
      <ul>
         <li>Use File Explorer to copy and paste the entire contents of the Windows product DVD or ISO to the USB flash drive.</li>
         <li>Optional: add an unattend file to automate the installation process. For more information, see Automate Windows Setup.</li>
      </ul>
      <li>Install Windows to the new PC.</li>
         <ul>
            <li>Connect the USB flash drive to a new PC.</li>
            <li>Turn on the PC and press the key that opens the boot-device selection menu for the computer, such as the Esc/F10/F12 keys. Select the option that boots the PC from the USB flash drive.</li>
            <li>Windows Setup starts. Follow the instructions to install Windows.</li>
            <li>Remove the USB flash drive</li>
         </ul>
   </ol>

<li><h2>Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download</h2></li>
   <ul>
      <li>Go to the <a href = "https://code.visualstudio.com/Download">Visual Studio Code download page<a/></li>
      <li>Choose the correct installer for your operating system (Windows, macOS, or Linux).</li>
      <li>Follow the on-screen instructions to download the installer.</li>
      <li>Run the installer and follow the setup wizard.</li>
      <li>Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.</li>
      <li>In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development.</li>
      <li>If needed, you can customize the installation by clicking on the "Individual components" tab in the installer and selecting or deselecting specific components.</li>
      <li>Click the "Install" button to start the installation process.</li>
      <li>This may take some time, as it involves downloading and installing the selected components.</li>
      <li>Once the installation is complete, launch Visual Studio.</li>
      <li>Sign in with your Microsoft account or create one if prompted.</li>
      <li>On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.</li>
      <li>You're now ready to start coding! Create a new project or open an existing one to begin your development work.</li>
    </ul>
    <ul>
      <li></li>
    </ul>


<li><h2>Set Up Version Control System:
   Install Git and configure it on your local machine. </h2></li>
   <ul>
      <li>Go to the <a href = "https://git-scm.com/">Git official website<a/></li>
      <li>Click on "Download" and choose your operating system.</li>
      <li>Run the installer and follow the setup instructions. You can leave most settings at their defaults.</li>
   </ul>
   Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   <ul>
      <li>Go to the <a href = "https://github.com/">Github<a/></li>
      <li>Click on "Sign up" and fill in the required information: username, email, and password.</li>
      <li>Complete the verification process and set up your profile.</li>
   </ul>

<li><h2>Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.</h2></li>
   <ul>
      <li>Visit the <a href="https://www.python.org/downloads/">python official page</a> to download the latest release ofPython.</li>
      <li>Select the python version to download</li>
      <li>Click on the Install Now</li>
      <li>Double-click the executable file, which is downloaded</li>
      <li>Select Customize installation and proceed.</li>
      <li>Click on the Add Path check box, it will set the Python path automatically.</li>
      <li>We can also click on the customize installation to choose desired location and features. Other important thing is install launcher for the all user must be checked.</li>
   </ul>

<li><h2>Install Package Managers:
   If applicable, install package managers like pip (Python).</h2></li>
   <ul>
      <li>Pip is included with Python 3.4 and later. To verify, open a terminal and run:</li>
      <li>If pip is not installed, download get-pip.py from <a href="https://bootstrap.pypa.io/get-pip.py">pip's official site</a></li>
   </ul>

<li><h2>Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html</h2></li>
   <ul>
      <li>Go to the<a href="https://dev.mysql.com/downloads/installer/">MYSQL official download page</a></li>
      <li>Run the installer and follow the setup instructions. Choose the "Developer Default" setup type.</li>
      <li>Configure MySQL server, set the root password, and complete the installation.</li>
   </ul>

<li><h2>Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.</h2></li>
   <ol>
      <li>Create a new file named Dockerfile in your project directory.</li>
      <li>Add the following content to the Dockerfile for a Python project:<img src="/screenshots/docker/Screenshot 2024-06-18 105832.png" /></li>
      <li>Build the Docker image using the Dockerfile:<img src="/screenshots/docker/Screenshot%202024-06-18%20105840.png" /></li>
      <li>Run the Docker container: <img src="/screenshots/docker/Screenshot 2024-06-18 105846.png"/></li>
      <li>Docker Compose for Multi-Container Applications</li>
         <ul>
            <li>Create a new file named docker-compose.yml in your project directory.</li>
            <li>Add the following content to define the services:<img src="/screenshots/docker/Screenshot 2024-06-18 105855.png" /></li>
            <li>Run Docker Compose:<img src="/screenshots/docker/Screenshot 2024-06-18 105901.png" /></li>
         </ul>
   </ol>
   <ol>
      <li>Install VirtualBox</li>
         <ul></ul>
            <li>Download VirtualBox from the <a href="https://www.virtualbox.org/">official VirtualBox website</a></li>
            <li>Run the installer and follow the instructions to install VirtualBox.</li>
      <li>Create a new VM</li>
         <ul></ul>
            <li>Open VirtualBox and click on "New" to create a new virtual machine.</li>
            <li>Configure the VM settings (e.g., name, type, and version). For example, create an Ubuntu VM.</li>
            <li>Allocate memory and hard disk space as needed.</li>
      <li>Install the Operating System</li>
         <ul></ul>
            <li>Download an ISO image of the operating system you want to install </li>
            <li>Start the VM and select the downloaded ISO image to install the OS.</li>
            <li>Follow the installation steps within the VM to set up the operating system.</li>
      <li>Set Up the Development Environment</li>
         <ul></ul>
            <li>Install necessary software within the VM, such as Python, Git, VS Code, etc.</li>
            <li>Configure the environment (e.g., set up virtual environments, install dependencies).</li>
            <li>Share folders between your host machine and the VM to facilitate file access.</li>
   </ol>

<li><h2>Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.</h2></li>
   <ul>
      <ol>
         <li>Python by Microsoft</li>
            <ul>
               <li>Provides rich support for the Python language, including features like IntelliSense (Pylance), linting, debugging, code navigation, and more.</li>
               <li>Installation: Search for "Python" in the VS Code Extensions Marketplace and install the one published by Microsoft.</li>
               <li>Features</li>
                  <ul>
                     <li>Syntax highlighting</li>
                     <li>Code linting with pylint or flake8</li>
                     <li>Debugging support</li>
                     <li>IntelliSense for autocompletion and code navigation</li>
                  </ul>
            </ul>
         <li>Prettier -Code formatter</li>
            <ul>
               <li>An opinionated code formatter that supports multiple languages, ensuring consistent code style across your project.</li>
               <li>Installation: Search for "Prettier - Code formatter" in the Extensions Marketplace and install it.</li>
               <li>Features</li>
                  <ul>
                     <li>Automatically formats code on save</li>
                     <li>Code linting with pylint or flake8</li>
                     <li>Configurable options via .prettierrc file</li>
                  </ul>
            </ul>
         <li>ESLint</li>
            <ul>
               <li>Integrates ESLint into VS Code, which is a pluggable linting utility for JavaScript and JSX.</li>
               <li>Installation: Search for "ESLint" in the Extensions Marketplace and install it.</li>
               <li>Features</li>
                  <ul>
                     <li>Identifies and fixes problems in JavaScript code</li>
                     <li>Customizable rules and configurations</li>
                     <li>Supports modern JavaScript and TypeScript</li>
                  </ul>
            </ul>
         <li>GitLens - Git supercharged</li>
            <ul>
               <li>Enhances the built-in Git capabilities in VS Code, providing a wealth of features to help you understand and work with your Git repositories.</li>
               <li>Installation: Search for "GitLens" in the Extensions Marketplace and install it.</li>
               <li>Features</li>
                  <ul>
                     <li>Visualize code authorship with Git blame annotations</li>
                     <li>Navigate and explore Git repositories with a GitLens explorer</li>
                     <li>View Git history, compare branches, and more</li>
                  </ul>
            </ul>
      <ol>
   </ul>

<li><h2>Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.</h2></li> 
    <ul>
      <li>Windows 11: Installed using the Installation media.</li>
      <li>VS Code: Downloaded and installed with default settings.</li>
      <li>Git: Downloaded, installed, and initialized a repository.</li>
      <li>GitHub: Account created and repository connected.</li>
      <li>Python and Pip: Installed with Python installer, verified Pip.</li>
      <li>MySQL: Installed and configured using the MySQL Installer.</li>
    </ul>
</ol>
This file contains the <a href="https://docs.google.com/document/d/1IAU72NrwUQw-OY3l39LImm8xwyXqY1jOiRUDv9osT9o/edit?usp=drive_link">screenshots</a>
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
