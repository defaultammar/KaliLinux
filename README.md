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

---

## 2. Important Shell Commands (Memorize These)

We'll divide commands into categories:

### **Basic Navigation**
```bash
pwd           # show current directory
ls            # list files
cd folder/    # change directory
cd ..         # go up one level
