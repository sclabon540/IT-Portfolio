# Linux Fundamentals Lab

## Project Overview

This project documents my hands-on practice with Linux fundamentals using Ubuntu on Windows Subsystem for Linux (WSL).

The goal was to learn basic Linux commands and develop foundational skills relevant to IT support and entry-level cybersecurity.

## Objectives

- Navigate the Linux file system.
- Create and manage files and directories.
- Read, copy, rename, and delete files.
- Inspect and modify file permissions.
- Check basic system and disk information.

## Skills and Commands Practiced

### 1. Navigation and Directories

| Command | Purpose |
|---|---|
| `pwd` | Display the current directory |
| `ls` | List files and directories |
| `cd` | Change directories |
| `mkdir` | Create a directory |
| `touch` | Create an empty file |

### 2. File Management

| Command | Purpose |
|---|---|
| `echo` | Write text to a file or display text |
| `cat` | Display file contents |
| `cp` | Copy files |
| `mv` | Move or rename files |
| `rm` | Remove files |

### 3. File Permissions

| Command | Purpose |
|---|---|
| `ls -l` | View file permissions and ownership |
| `chmod o-r notes.txt` | Remove read permission for other users |
| `chmod o+r notes.txt` | Restore read permission for other users |

I verified the permission changes and restored the original permissions.

### 4. System Information

| Command | Purpose |
|---|---|
| `uname -a` | Display kernel and system information |
| `whoami` | Display the current username |
| `df -h` | Display disk space usage |
| `free -h` | Display memory usage |
| `date` | Display the system date and time |

## Lab Results

I created a `linux-lab` directory and practiced managing a file named `notes.txt`. I also inspected its permissions, changed read access for other users, and restored the original permissions.

These exercises helped me understand how Linux commands support file management, system checks, and basic access control.

## Lessons Learned

- Linux commands are case-sensitive.
- The terminal provides a direct way to manage files and inspect a system.
- File permissions help control access to information.
- Commands such as `rm` can delete files, so filenames should be checked before execution.
- Verifying command results is an important troubleshooting habit.

## Future Improvements

- Practice Linux users and groups.
- Learn process management and basic networking commands.
- Practice reading system logs.
- Capture terminal screenshots as evidence of completed exercises.

## Environment

- Operating system: Ubuntu Linux
- Environment: Windows Subsystem for Linux (WSL)
- Skill level: Beginner
