Linux Fundamentals 2 Practice
What I Did

This lab demonstrates intermediate Linux CLI skills: file permissions, su command, reading logs, creating and moving files, and checking folder contents.

Steps Taken
1. File Permissions

Checked permissions with:

ls -l


Learned how to read permissions like:

-rwxr-xr--


Broke down into:

First character → file type (- regular, d directory)

Next three → owner permissions (rwx)

Next three → group permissions (r-x)

Last three → others (r--)

2. Switching Users with su

Command:

su username


Used to temporarily gain another user’s privileges, often root.

Verified user with:

whoami


Learned the security principle: only elevate privileges when necessary to avoid leaving root access on accidentally.

3. Reading Logs (/var/log)

Checked system logs:

cat /var/log/syslog
cat /var/log/auth.log


Learned to use logs for troubleshooting and security monitoring.

Some logs require root access:

sudo cat /var/log/auth.log

4. File Management Recap

Creating files with touch

Adding text with echo "text" > file

Moving files with mv

Deleting files with rm

Listing multiple folders at once:

ls -1 ~/github/1 ~/github/2

5. Skills Demonstrated

Understanding and reading file permissions

Switching users safely with su

Checking current user (whoami)

Reading and analyzing log files in /var/log

Managing files and folders (touch, echo, mv, rm)

Listing folder contents clearly and efficiently