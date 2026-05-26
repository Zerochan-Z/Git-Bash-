# Git-Bash-
Git Bash - terminal for week 3 learning as UTAR June intake student. (25/05)

## 📁 Git Bash – Intermediate Basics Table

---

### Navigation

| Command | Function |
|---------|----------|
| `pwd` | Print current directory path |
| `ls` | List files and folders |
| `ls -la` | List all files (including hidden) with details |
| `cd` | Change directory |
| `cd ..` | Go to parent directory |
| `cd ~` | Go to home directory |
| `cd /` | Go to root directory |

---

### File & Folder Management

| Command | Function |
|---------|----------|
| `mkdir` | Create a new folder |
| `mkdir -p` | Create nested folders |
| `touch` | Create a new empty file |
| `rm` | Delete a file |
| `rm -r` | Delete a folder and contents |
| `rm -rf` | Force delete (no warning) |
| `cp` | Copy a file |
| `cp -r` | Copy a folder |
| `mv` | Move or rename file/folder |

---

### Viewing & Editing

| Command | Function |
|---------|----------|
| `cat` | Display file content |
| `head` | Show first 10 lines of file |
| `head -n` | Show first N lines of file |
| `tail` | Show last 10 lines of file |
| `tail -n` | Show last N lines of file |
| `notepad` | Open file in Notepad (Windows) |
| `start` | Open file with default program |
| `code` | Open file in VS Code |

---

### Writing to Files

| Command | Function |
|---------|----------|
| `echo >` | Write text to file (overwrites) |
| `echo >>` | Append text to file |
| `cat >` | Type directly into file |

---

### Python

| Command | Function |
|---------|----------|
| `python` | Run Python script or enter interactive mode |
| `exit()` | Exit Python interactive mode |
| `pip install` | Install Python package |
| `pip list` | Show installed packages |

---

### Special Symbols

| Symbol | Function |
|--------|----------|
| `.` | Current directory |
| `..` | Parent directory |
| `~` | Home directory |
| `/` | Root directory or folder separator |
| `*` | Anything starts with / Everything / *{file}* |
| `>` | Redirect output (overwrite) |
| `>>` | Redirect output (append) |

---

### Keyboard Shortcuts

| Shortcut | Function |
|----------|----------|
| `Tab` | Auto‑complete file/folder names |
| `↑` | Previous command |
| `↓` | Next command |
| `Ctrl + C` | Stop current process |
| `Ctrl + L` | Clear screen |
| `Ctrl + A` | Jump to beginning of line |
| `Ctrl + E` | Jump to end of line |
| `Ctrl + U` | Delete from cursor to line start |
| `Ctrl + K` | Delete from cursor to line end |
| `Ctrl + W` | Delete previous word |
| `Ctrl + R` | Search command history |
| `Ctrl + Insert` | Copy |
| `Shift + Insert` | Paste |

---

### Git Commands

| Command | Function |
|---------|----------|
| `git init` | Initialize Git repository |
| `git status` | Check file status |
| `git add` | Stage a file |
| `git add .` | Stage all files |
| `git commit -m` | Commit staged files with message |
| `git push` | Upload to GitHub |
| `git pull` | Download from GitHub |
| `git clone` | Copy a remote repository |

---

### Error Troubleshooting

| Error | Function (What it means) |
|-------|--------------------------|
| `command not found` | Typo or command not installed |
| `No such file or directory` | Wrong path or typo |
| `python: command not found` | Python not in PATH |
| `cannot delete: Directory not empty` | Folder has files inside |
| `permission denied` | No permission for file |

---

## Complete Command Summary

| Step | Command | What it does |
|------|---------|--------------|
| 1 | `ls` | Check current files |
| 2 | `touch move_csv.sh` | Create script file |
| 3 | `notepad move_csv.sh` | Open for editing |
| 4 | (type script in Notepad) | Write the commands |
| 5 | `chmod +x move_csv.sh` | Make executable |
| 6 | `./move_csv.sh` | Run the script |
| 7 | `ls` | Verify result |

---

## What Each Line in the Script Does

| Line | Meaning |
|------|---------|
| `#!/bin/bash` | "Run this with Bash interpreter" |
| `mkdir -p csv_files` | "Create folder named csv_files (don't error if exists)" |
| `mv *.csv csv_files/` | "Move all files ending with .csv into that folder" |

---
