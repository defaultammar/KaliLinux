# Kali Linux Beginner Guide

In this article, we’ll cover the **basic requirements** to install Kali Linux and the **essential commands** you need to start learning it effectively.

---

## 🖥️ Minimum Recommended Specs for Kali

> `CPU: Dual-core 64-bit (Intel i5 or Ryzen 3 and up is better)`  
> `RAM: 4 GB min (8 GB+ ideal)`  
> `Storage: 20 GB min (40+ GB recommended)`

---

## 1. Understand the File System Structure

Kali Linux is not like Windows. It's a powerful, command-line-based system used for security and development tasks.

Here are key directories and their purposes:

| **Directory**       | **Purpose**                                  |
|---------------------|----------------------------------------------|
| `/`                 | Root of everything                           |
| `/home/username`    | Your personal files (like C:\Users)          |
| `/etc`              | Configuration files                          |
| `/bin`              | Essential binaries (commands)                |
| `/var/log`          | Log files                                    |
| `/opt`              | Optional software                            |
| `/tmp`              | Temporary files                              |
| `/root`             | Admin (root) user’s home directory           |

----

## 2. Important Shell Commands (Memorize These)

We'll divide commands into categories:

### **Basic Navigation**
```bash
| pwd           | # show current directory
| ls            | # list files
| cd folder/    | # change directory
|cd ..          | # go up one level
```



### **File Management**
```bash
|mkdir test_folder        | # create folder
|touch file.txt           | # create empty file
|rm file.txt              | # delete file
|rm -r folder/            | # delete folder recursively
|cp a.txt b.txt           | # copy file
|mv a.txt /home/          | # move/rename file
```
### **View File Content**
```bash
|cat file.txt             | # view content
|less file.txt            | # scroll through file
|head file.txt            | # view first 10 lines
|tail file.txt            | # view last 10 lines
```
-----
And the 3rd is
# 3. Permissions and Ownership

```
|ls -l                  |  # show file permissions
|chmod +x file.sh       |  # make a script executable
|chown user:group file  |  # change file owner
```
----

# 4. Package Management (Debian/Kali)
```bash

|sudo apt update           |   # update package list
|sudo apt upgrade          |  # upgrade all packages
|sudo apt install nmap     |   # install a tool
|sudo apt remove toolname  |   # uninstall a tool
```
-----

# 5. User Management
```bash

|whoami                     | # show current user
|sudo su                    | # become root (admin)
|adduser newuser            | # add a new user
|passwd newuser             | # set user password
```
----
# 6. Networking Tools
```bash

|ifconfig                    | # show network info (older)
|ip a                        | # show IP address (preferred)
|ping 8.8.8.8                | # test connection
|netstat -tuln               | # show open ports
```
----

# 7. Useful Shortcuts
> `TAB` → Auto-complete commands or paths

> `CTRL + C` → Stop a running command

>`CTRL + L` → Clear the terminal

>`history` → Show previous commands

>`!!` → Run the last command again

------
# 8. Scripts & Tools
Create and run a simple script:

```bash

nano myscript.sh
Add this inside:
```
---
```bash

#!/bin/bash
echo "Hello, hacker"
Make it executable and run:
```
---
```bash
chmod +x myscript.sh
./myscript.sh
```
# 9. Search & Find

```bash
grep "word" file.txt        # search for a word in a file
find / -name file.txt       # search for a file by name
```
----
# 10. Logs & Monitoring

```bash
dmesg                       # system messages
top                         # show running processes
htop                        # advanced process viewer
tail -f /var/log/syslog     # view live system logs
```
----
🧪 Ready to Practice?

**Try all commands in a Virtual Machine or use free online labs:**

> `https://www.webminal.org/`

> `https://linuxzoo.net/`

# 📌 Legal Disclaimer
```
This guide is for educational purposes only. Do not attempt to use these tools on any system you do not own or have explicit permission to test.
```



***Want To Download This File Here A link***
https://docs.google.com/document/d/16DtgcO15-lDjqIKvJftQrXjuvA77I18_XplpA1MTCiA/edit?usp=sharing





**Written By Mirza Ammar Cyber Warrior**
