Linux 
1.Navigation:
* ls - list directory contents
* ls -la - lsist all files with details
* cd /path - change to path
* cd .. - go to parent directory
* cd ~ - go to home directory
* tree - display directories as a tree

2.Files and Directories:
* touch file.txt - create an empty file
*vim file.txt – text editor
* cat file.txt -  prints or display file contents
* mkdir - create a directory
* mkdir -p - create nested directories
* cp - copy a file or directory
* cp -r - copy a directory recursively
* mv - move a file or directory
* rm - remove a file
* rmdir - remove an empty directory

3.File Permission and Ownership:
* chmod 777 file name - permission decide who can read, write or execute a file
* chmod 755 file name - set rwx (user-access all the 3), r-x(group-access only read&write), r-x (-everyone-same permission for also 3) permission
* chown user:group file name - change owner and group
* chgrp group file name - change group ownership

4.Process Management:
* ps aux - list all processes with details
* top - interactive process viewer
* htop - enhanced process viewer(human readable format)  
* pkill name - send signals by process name
* kill PID number - kill by PID number

5.System info and Logs maintain:
* vmstat - virtual memory statistics
* free -h - memory and swap usage (human readable format)
* free -m - memory usage
* df -h - show the available space, size in readable format
* lsblk - show the disk details
* fdisk - show the disk paritition in table
* ip -a - show the IP address
* curl - HTTP request
* wget link - download a file
 Bash Script:
* Bash is a Scripting Language.
* Bash is the default shell in linux operating systems.
* #!/bin/bash – shebang command that only it take as bash file 
* Bash file extension is sh
* ls - list directory contents
* ls -la - list all files with details
* Touch script.sh (file name) – create a new file in bash
* Vim file.name – text editor
* rm file.name -remove the script file
* echo - Prints text to the terminal window
* Bash file name – to run the bash file or view the output
 Variable Declaration: 
* $ - Dollar symbol is used to call the variable in bash.
Name = ”harini”
Age=15
Echo “My name is $Name”
Echo “My age is $Age”
* Cronjob – Automation
* Cron – time based job
* Crontab -l =list 
* Crontab -e =edit
* Crontab -r =entire cronjob delete
 Github :
1.Setup & Configuration:
* git config --global user.name “Your Name”
* git config --global user.email “ your email.id”
2.Repository Management:
* git init -Initialize a new repo
* git clone “repo link” - Clone an  repo
3.Basic Workflow:
* git status - Check changes
* git add . - Stage all changes
* git commit -m "Your Commit message" - Commit staged changes
* git push origin main - Push to GitHub
* git pull origin main - Pull latest changes
4.Branching & Merging:
* git branch branch.name - Create branch
* git checkout branch.name - Switch branch
* git merge branch.name - Merge into current branch
* git log – it show the commit 
* git log --oneline -it  show the commit in one line





