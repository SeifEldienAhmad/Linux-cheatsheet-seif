# Linux Commands Cheatsheet  
**By Seif Eldein Ahmad Mohammad**

---

## 1. Terminal Basics

| Command | Description |
|--------|-------------|
| `pwd` | Show current directory |
| `ls` | List files and folders |
| `ls -la` | List all (including hidden) with details |
| `cd folder/` | Move into a folder |
| `cd ..` | Go back one level |
| `clear` | Clear the terminal screen |
| `exit` | Close the terminal session |

---

## 2. File & Directory Management

| Command | Description |
|---------|-------------|
| `touch file.txt` | Create empty file |
| `nano file.txt` | Open file in nano editor |
| `cat file.txt` | Display file content |
| `cp source.txt dest.txt` | Copy file |
| `mv old.txt new.txt` | Rename or move file |
| `rm file.txt` | Delete file |
| `mkdir folder` | Create new folder |
| `rm -r folder/` | Delete folder and contents |

---

## 3. Viewing Files

| Command | Description |
|---------|-------------|
| `cat file` | Show file content |
| `less file` | Scroll through file |
| `head -n 10 file` | Show first 10 lines |
| `tail -n 10 file` | Show last 10 lines |

---

## 4. Searching

| Command | Description |
|---------|-------------|
| `find . -name file.txt` | Find file by name |
| `grep "text" file.txt` | Search for text in a file |
| `grep -r "text" folder/` | Recursive search in directory |

---

## 5. User Management

| Command | Description |
|---------|-------------|
| `whoami` | Show current user |
| `id` | Show user and group IDs |
| `users` | Show logged-in users |
| `sudo command` | Run command as root (admin) |

---

## 6. File Permissions

| Command | Description |
|---------|-------------|
| `ls -l` | View file permissions |
| `chmod +x script.sh` | Make script executable |
| `chown user file` | Change file owner |

---

## 7. Disk & System Info

| Command | Description |
|---------|-------------|
| `df -h` | Show disk space |
| `du -sh folder/` | Folder size |
| `free -h` | RAM usage |
| `uptime` | How long system has been running |
| `uname -a` | System information |

---

## 8. Process Management

| Command | Description |
|---------|-------------|
| `ps aux` | Show all processes |
| `top` | Live process monitor |
| `kill PID` | Stop process by ID |
| `killall name` | Stop all processes with name |

---

## 9. Archives & Compression

| Command | Description |
|---------|-------------|
| `tar -cvf archive.tar folder/` | Create tar archive |
| `tar -xvf archive.tar` | Extract tar archive |
| `zip archive.zip file` | Create zip |
| `unzip archive.zip` | Extract zip |

---

## 10. Package Management (Debian/Ubuntu)

| Command | Description |
|---------|-------------|
| `sudo apt update` | Update package lists |
| `sudo apt upgrade` | Upgrade packages |
| `sudo apt install packagename` | Install package |
| `sudo apt remove packagename` | Remove package |

---

**Author**: Seif Eldein Ahmad Mohammad  
**GitHub**: [https://github.com/SeifEldienAhmad](https://github.com/SeifEldienAhmad)  
**LinkedIn**: [linkedin.com/in/seif-ahmed-2263362bb](https://linkedin.com/in/seif-ahmed-2263362bb)

---

*Feel free to fork, clone, and build upon this as I grow in Linux and Cybersecurity!*
