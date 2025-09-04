# Linux Fundamentals 1

**Description:**  
This repository contains exercises and examples from Linux Fundamentals 1. It demonstrates basic Linux commands, file creation, text manipulation, and navigating the command line, providing foundational skills for Linux system administration.  

**Skills Learned:**  
- Navigating the Linux CLI  
- Creating files with `touch` and `echo`  
- Appending and overwriting text in files  
- Viewing file contents and checking existence  
- Searching for text patterns in files using `grep`  
- Using absolute paths for efficient file access  

---

## Basic CLI Commands

**Key Commands/Concepts:**  
- `pwd` → Print Working Directory  
- `ls` → List files and folders  
- `cd` → Change directory  
- `cat` → View contents of a file  
- `touch` → Create an empty file  
- `echo` → Create a file with text or print text to terminal  
- `>` → Overwrite a file with new text  
- `>>` → Append text to an existing file  

**Examples:**  
- `ls folder4` – check contents of `folder4`  
- `cat folder4/note.txt` – display contents of `note.txt`  
- `cd folder4` – change into `folder4`  
- `pwd` – print current working directory  

**Artifacts:**  
- Screenshots of commands stored in `images/` folder  

---

## Linux File Creation Practice

**Description:**  
This lab focused on creating files in Linux using `echo` to add content and `touch` to create empty files. It demonstrated basic file creation and text manipulation from the command line.  

**Key Commands/Concepts:**  
- `echo "text" > filename` – creates a file with specified text  
- `touch filename` – creates an empty file  
- `>>` – append text to an existing file  

**Examples from Lab:**  
- `echo "Hi GitHub, Guy here showing off my files" > GuyReadMe`  
  - Creates `GuyReadMe` containing the text  
- `touch "GuyDon'tReadMe.txt"`  
  - Creates an empty file  
- `echo "Another line added" >> GuyReadMe`  
  - Appends text without removing previous content  
- `cat GuyReadMe`  
  - Prints file contents  
- `ls -l`  
  - Lists files with size, permissions, etc.  

**Outcome:**  
Successfully created files with and without content, appended text, and verified contents and file properties.  

**Artifacts:**  
- Screenshots or terminal output stored in `images/` folder  

---

## Using `grep` with Absolute Paths

**Description:**  
This lab focused on using the `grep` command to search for specific text patterns in files using absolute paths. It demonstrates how to efficiently locate information without navigating through directories manually.  

**Key Commands/Concepts:**  
- `grep "text" /absolute/path/to/file` – search for a string in a specific file  
- Absolute path usage avoids the need to `cd` into directories before searching  

**Examples from Lab:**  
- `grep "THM" /home/tryhackme/access.log`  
  - Searches the file `access.log` for the string `"THM"` using the absolute path  

**Outcome:**  
Successfully located specific text in files using `grep` and absolute paths, demonstrating efficient file searching and text pattern recognition on the Linux command line.  

**Artifacts:**  
- Screenshots of terminal output stored in `images/` folder


