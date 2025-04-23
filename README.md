# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
![Screenshot from 2025-03-26 13-38-24](https://github.com/user-attachments/assets/36f214a7-55cf-4eb6-874c-75101d23a2c2)

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
![Screenshot from 2025-03-26 14-00-28](https://github.com/user-attachments/assets/29c3826d-1e4b-4672-9734-ae39d4af2019)

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
![Screenshot from 2025-03-26 14-01-25](https://github.com/user-attachments/assets/f13f5ecf-20ca-4a2c-92cd-85aa76d8b2c7)

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
![Screenshot from 2025-03-26 14-01-43](https://github.com/user-attachments/assets/cb8752dc-699d-437c-9649-d8053c327814)

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
![Screenshot from 2025-03-26 14-02-04](https://github.com/user-attachments/assets/5479541a-5072-4504-a987-8ab5d852530e)

### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
![Screenshot from 2025-03-26 14-09-04](https://github.com/user-attachments/assets/96b0ba4a-18ff-448c-8b69-714eec632de9)

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
![Screenshot from 2025-03-26 14-11-59](https://github.com/user-attachments/assets/38b7c52e-e866-4b22-bad5-4868f9ebb570)

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
![Screenshot from 2025-03-26 14-11-59](https://github.com/user-attachments/assets/38b7c52e-e866-4b22-bad5-4868f9ebb570)

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
![Screenshot from 2025-03-26 14-13-20 (1)](https://github.com/user-attachments/assets/8c5cdd4a-ca85-47da-9002-0f8be6181865)

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
![Screenshot from 2025-03-26 14-14-06](https://github.com/user-attachments/assets/aeff1580-c713-4f94-94c0-846e8a283edc)

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
![Screenshot from 2025-03-26 14-22-04](https://github.com/user-attachments/assets/7b8bb790-b804-4584-b6c2-bcf912e90465)

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
![Screenshot from 2025-03-26 14-26-32](https://github.com/user-attachments/assets/e014dfff-ffe1-46c9-b42e-482bd40cd8ff)

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
![Screenshot from 2025-03-26 14-27-50 (2)](https://github.com/user-attachments/assets/f001d781-8a5e-4d35-872e-aefadc42faf5)

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
![Screenshot from 2025-03-26 14-28-31](https://github.com/user-attachments/assets/336ab0db-dc83-42a9-8c79-4bb12f3cddd9)

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
![Screenshot from 2025-03-26 14-33-21](https://github.com/user-attachments/assets/b440c9d6-4785-42f6-84f1-4ced502ac314)

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
![Screenshot from 2025-03-26 14-35-39 (2)](https://github.com/user-attachments/assets/9324fbdc-992f-40e3-bb9b-56a6e43df087)

### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
![Screenshot from 2025-03-26 15-11-45](https://github.com/user-attachments/assets/9286e7fc-29a7-46f5-81c2-c41f1bbe9106)

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
![Screenshot from 2025-03-26 14-35-39 (3)](https://github.com/user-attachments/assets/92125f60-268b-4631-b8d8-299438e9d21f)

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
![Screenshot from 2025-03-26 15-59-16 (1)](https://github.com/user-attachments/assets/40224770-4286-4620-b922-214078b209e3)

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
![Screenshot from 2025-03-26 15-25-17 (1)](https://github.com/user-attachments/assets/056921b2-afd5-41df-93e9-e01c7cc62fda)

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
![Screenshot from 2025-03-26 15-27-46 (1)](https://github.com/user-attachments/assets/630eb953-0b2a-48ea-8a5b-194372d91fc9)

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
![Screenshot from 2025-03-26 15-59-16](https://github.com/user-attachments/assets/46493e0d-ad19-4a7e-a7d9-7c49f6169954)

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
![Screenshot from 2025-03-26 16-00-12](https://github.com/user-attachments/assets/7345a486-3f3b-42ea-b7fd-b31b6a8e1283)

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
![Screenshot from 2025-03-26 16-01-44 (1)](https://github.com/user-attachments/assets/c37b4b7b-85bf-4c9d-8cf3-313263645f91)

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
![Screenshot from 2025-03-27 11-27-44 (1)](https://github.com/user-attachments/assets/c4b69f4b-84df-4ee1-b577-34c3cae3224f)

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
![Screenshot from 2025-03-27 11-28-27 (1)](https://github.com/user-attachments/assets/41382087-0ca0-442e-af35-17649ed57dff)

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
![Screenshot from 2025-03-27 11-29-16 (1)](https://github.com/user-attachments/assets/c31ae511-55d2-4982-812c-c9433ad9c994)

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
![Screenshot from 2025-03-27 11-49-43](https://github.com/user-attachments/assets/526006cc-8d4e-41c9-89be-020b66139c48)

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
![Screenshot from 2025-03-27 12-47-15](https://github.com/user-attachments/assets/ccd614c3-bdbf-4d14-8bd5-dbb11217cdd5)

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
![Screenshot from 2025-03-27 12-49-15](https://github.com/user-attachments/assets/a59e764c-3696-4eee-8ea5-9d199798443d)

## Result
Successfully performed the series of Linux commands as specified.
