# Termux Commands Guide

Welcome to the comprehensive guide on essential Termux commands. This document covers 30 useful commands with their descriptions to enhance your Termux experience.

## Table of Contents

1. [Basic Commands](#basic-commands)
2. [File and Directory Operations](#file-and-directory-operations)
3. [Network and System Monitoring](#network-and-system-monitoring)
4. [Package Management](#package-management)
5. [Programming and Development](#programming-and-development)

---

## Basic Commands

1. **`pwd`**  
   Displays the current working directory.

2. **`ls`**  
   Lists files and directories in the current directory. Use `ls -l` for detailed listing and `ls -a` to include hidden files.

3. **`cd [directory]`**  
   Changes the current directory to `[directory]`.

4. **`mkdir [directory]`**  
   Creates a new directory named `[directory]`.

5. **`rm [file]`**  
   Removes the file named `[file]`. Use `rm -r [directory]` to remove a directory and its contents recursively.

---

## File and Directory Operations

6. **`cp [source] [destination]`**  
   Copies `[source]` to `[destination]`.

7. **`mv [source] [destination]`**  
   Moves or renames `[source]` to `[destination]`.

8. **`cat [file]`**  
   Displays the contents of `[file]` on the terminal.

9. **`nano [file]`**  
   Opens `[file]` in the Nano text editor for editing.

10. **`chmod [permissions] [file]`**  
    Changes the permissions of `[file]` according to `[permissions]` (e.g., `chmod 755 script.sh`).

11. **`grep [pattern] [file]`**  
    Searches for `[pattern]` in `[file]` and displays matching lines.

12. **`find [path] -name [filename]`**  
    Searches for files named `[filename]` in the directory tree rooted at `[path]`.

13. **`tar -czvf [archive.tar.gz] [directory]`**  
    Creates a compressed archive of `[directory]` named `[archive.tar.gz]`.

14. **`unzip [file.zip]`**  
    Extracts the contents of `[file.zip]`.

15. **`df -h`**  
    Displays disk space usage in a human-readable format.

---

## Network and System Monitoring

16. **`ping [host]`**  
    Sends ICMP ECHO_REQUEST packets to `[host]` to check connectivity.

17. **`curl [url]`**  
    Fetches the content from `[url]`.

18. **`wget [url]`**  
    Downloads files from `[url]`.

19. **`top`**  
    Displays a dynamic view of system processes.

20. **`ps aux`**  
    Lists all running processes with detailed information.

21. **`netstat -tuln`**  
    Displays network connections and listening ports.

22. **`ifconfig`**  
    Shows network interface configuration.

23. **`uptime`**  
    Shows how long the system has been running along with load averages.

24. **`traceroute [host]`**  
    Traces the route packets take to reach `[host]`.

---

## Package Management

25. **`pkg update`**  
    Updates the package lists to the latest versions.

26. **`pkg upgrade`**  
    Upgrades all installed packages to their latest versions.

27. **`pkg install [package]`**  
    Installs the `[package]` specified.

28. **`pkg search [package]`**  
    Searches for `[package]` in the repositories.

29. **`pkg remove [package]`**  
    Removes the `[package]` specified.

30. **`pkg list-installed`**  
    Lists all installed packages.

---

Feel free to explore these commands to get the most out of Termux. For further assistance, refer to the [Termux Wiki](https://wiki.termux.com) and community forums.

