# shell-scripting1

# Shell Scripting Project

## Overview

This project focused on automating routine tasks using shell scripting in a Linux environment. The primary goal was to write and execute a shell script that can automatically create multiple folders and user accounts. Shell scripting is a vital tool for DevOps engineers and system administrators because it saves time, reduces repetitive tasks, and ensures consistency in task execution.

---

## Task 1: Create a Script on Ubuntu Server

### Step-by-Step Process

1. **Created a Project Directory**  
   I began by creating a dedicated folder for this project using the command:
   ```
   mkdir shell-scripting
   cd shell-scripting
   ```

2. **Created the Script File**  
   I used the vim text editor to create a new script file:
   ```
   vim my_first_shell_script.sh
   ```

3. **Wrote the Shell Script Code**  
   Inside the file, I entered the following code:
   ```
   #!/bin/bash

   # Create directories
   mkdir Folder1
   mkdir Folder2
   mkdir Folder3

   # Create users
   sudo useradd user1
   sudo useradd user2
   sudo useradd user3
   ```

4. **Saved and Exited vim**  
   :wq

5. **Verified Script Creation**  
   I listed the contents of the directory to confirm the script file exists:
   ```
   ls -la
   ```
![](https://github.com/adaezeokoduwa/shell-scripting1/blob/main/imgs/shell-script.jpg?raw=true)
---

## Task 2: Make the Script Executable and Run It

###  Step-by-Step Process

1. **Gave Execute Permission to the Script**  
   I used the `chmod` command to make the file executable:
   ```
   chmod +x my_first_shell_script.sh
   ```

2. **Ran the Script**  
   I executed the script using:
   ```
   ./my_first_shell_script.sh
   ```

3. **Tested That Folders Were Created**  
   I confirmed the folders were created using:
   ```
   ls
   ```
   Output included:
   ```
   Folder1  Folder2  Folder3
   ```

4. **Verified That Users Were Created**  
   I checked if the users exist using:
   ```
   id user1
  
   ```

   the command returned UID and GID info confirming the user creation.
![](https://github.com/adaezeokoduwa/shell-scripting1/blob/main/imgs/shell-script.jpg?raw=true)
---

## Conclusion

By completing these tasks, I gained hands-on experience with:
- Writing shell scripts using a text editor
- Automating folder and user creation
- Using Linux permissions (`chmod`)
- Running and verifying shell scripts

This task reinforced the importance of automation in system administration and how scripting boosts efficiency and accuracy.
