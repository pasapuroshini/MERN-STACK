# Git Setup and Workflow Guide for Windows Users

## **Installing Git**

### **Download Git:**
- Go to [Git Downloads](https://git-scm.com/) and download the appropriate version for Windows.
- Alternatively, search for "Git download" on Google.

### **Installation Process:**
1. Run the installer.
2. When prompted, click “Next” until you reach the installation options:
   - **Editor**: Choose `Notepad` (if you're not familiar with `vim`).
   - **Branch Name**: Choose `main` instead of `master`.
   - **Command Line Tool**: Select "Use Git from the command line".
3. Finish the installation.

### **Verify Installation:**
1. Open Command Prompt or PowerShell.
2. Run the following command:
   ```bash
   git --version

### Setting Up Git on Your Machine
- Configure Git with Your Name and Email
- Git tracks changes by associating commits with a name and email address. You need to configure these values so Git knows who you are when you make commits
  #### Set Your Username:
  ```
  git config --global user.name "Your Name"

### Set Your Email:
```
git config --global user.email "youremail@example.com"
```
#### Verify Your Configuration:
Run:
```
git config --list
```
This will display your username and email.
