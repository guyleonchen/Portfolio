Linux Fundamentals 1 & 2

Description:
This repository contains exercises and examples from Linux Fundamentals 1 and 2, covering basic to intermediate command-line skills. Labs include file creation and manipulation, searching with grep, user management, file permissions, log analysis, and efficient file operations.

Skills Learned
Fundamentals 1

Navigating the Linux CLI (cd, pwd, ls)

Creating and editing files (touch, echo)

Appending and overwriting text (>, >>)

Viewing file contents (cat)

Searching for text patterns with grep

Using absolute paths for efficient file access

Fundamentals 2

Reading and understanding file permissions (ls -l, chmod, chown)

Switching users safely with su and verifying identity (whoami)

Reading system and authentication logs (/var/log/syslog, /var/log/auth.log)

Creating, moving, deleting, and listing files efficiently (touch, echo, mv, rm, ls -1)

Key Commands & Examples
Basic CLI (Fundamentals 1)

pwd → print current directory

ls → list files and folders

cd folder4 → change directory

cat folder4/note.txt → view file contents

touch GuyDontReadMe.txt → create an empty file

echo "Hi GitHub" > GuyReadMe → create a file with text

echo "Another line" >> GuyReadMe → append text

grep "THM" /home/tryhackme/access.log → search for text in a file

File Permissions & User Management (Fundamentals 2)

ls -l → view detailed permissions

Example: -rwxr-xr--

- → file type

rwx → owner permissions

r-x → group permissions

r-- → others

su username → switch users temporarily

whoami → verify current user

sudo cat /var/log/auth.log → read logs requiring root privileges

File Management Recap

touch filename → create empty file

echo "text" > filename → create file with text

mv source destination → move file

rm filename → delete file

ls -1 folder1 folder2 → list multiple folders clearly

Outcomes

Successfully navigated the Linux filesystem and created, edited, and appended files.

Efficiently searched for text using grep and absolute paths.

Understood and interpreted file permissions and user privileges.

Safely switched users and analyzed system logs for troubleshooting and monitoring.

Managed files and directories using standard Linux commands.

Repository Structure

Linux-Fundamentals-1/ – Basic CLI, file creation, grep usage

Linux-Fundamentals-2/ – File permissions, user management, log reading, file operations

images/ – Screenshots demonstrating terminal commands and outputs
