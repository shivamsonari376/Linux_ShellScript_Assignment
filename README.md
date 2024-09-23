# For this assignment we were supposed to solve 10 questions on shell scripting. Following are the questions.
1. Create a Directory Structure:

Write a script that creates the following directory structure:

   /home/user/

       ├── projects/

       │   ├── project1/

       │   ├── project2/

       │   └── project3/

       ├── documents/

       └── downloads/


2. File Backup:

Write a script that takes a directory as an argument and creates a backup of all `.txt` files in that directory. The backup files should be copied to a new directory named `backup` with a timestamp.


3. User Information:

Write a script that displays the following information about the user:

   - Username

   - User ID

   - Group ID

   - Home Directory

   - Shell being used


4. Disk Usage Alert:

Write a script that checks the disk usage of the root filesystem. If the disk usage is above 80%, the script should send an email alert to the system administrator.


5. File Permission Checker:

Write a script that takes a file as an argument and checks if the file has read, write, and execute permissions. The script should display appropriate messages for each permission.


6. Automated Backup:

Write a script that compresses the `/home/user/documents` directory into a tarball named `documents_backup.tar.gz` and moves it to the `/home/user/backup` directory. This script should be scheduled to run daily using cron.


7. Process Monitor:

Write a script that checks if a specific process (e.g., `apache2`) is running. If the process is not running, the script should start the process and log the action to a file.


8. Text File Analysis:

Write a script that takes a text file as an argument and counts the number of lines, words, and characters in the file. The script should display the counts.


9. System Information Report:

Write a script that generates a system information report. The report should include:

   - System uptime

   - Memory usage

   - CPU load

   - Disk usage

   - Running processes

The report should be saved to a file named `system_report.txt`.


10. Simple Calculator:

Write a script that acts as a simple calculator. The script should prompt the user to enter two numbers and an operator (+, -, *, /) and then display the result of the operation.
