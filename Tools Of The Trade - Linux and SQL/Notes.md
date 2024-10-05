# Operating Systems & Linux Basics

## Table of Contents
- [Operating Systems](#operating-systems)
- [Hardware](#hardware)
- [Applications & Resource Allocation](#applications--resource-allocation)
- [Boot Process](#boot-process)
- [Virtualization](#virtualization)
- [User Interfaces](#user-interfaces)
  - [Graphical User Interface (GUI)](#graphical-user-interface-gui)
  - [Command Line Interface (CLI)](#command-line-interface-cli)
- [Linux Overview](#linux-overview)
  - [Components of Linux](#components-of-linux)
  - [Popular Linux Distros](#popular-linux-distros)
- [Penetration Testing Tools](#penetration-testing-tools)
- [Basic Linux Commands](#basic-linux-commands)
- [File Permissions & Ownership](#file-permissions--ownership)
- [Databases & SQL](#databases--sql)

---

## Operating Systems
An **Operating System (OS)** is the interface between the computer hardware and the user. It manages resources and provides a user-friendly interface.

- **Examples**: Windows, Linux, macOS.

---

## Hardware
**Hardware** refers to the physical components of a computer, like the CPU, RAM, storage devices, etc.

---

## Applications & Resource Allocation
- **Applications**: Programs that perform specific tasks (e.g., browsers, word processors).
- **Resource Allocation**: The OS manages resources and memory to ensure optimal performance.

---

## Boot Process
1. **BIOS** (Basic Input/Output System) or **UEFI** (Unified Extensible Firmware Interface) is activated when the computer boots.
2. It loads the **bootloader**, which starts the OS.

---

## Virtualization
- **Virtual Machine (VM)**: A software-based version of a physical computer.
- **Virtualization**: The process of creating virtual instances of hardware using software.

---

## User Interfaces

### Graphical User Interface (GUI)
A GUI uses icons and visuals to interact with the OS. It includes components like:
- **Start menu**
- **Taskbar**
- **Desktop icons**

### Command Line Interface (CLI)
The CLI is a text-based interface that uses commands to interact with the OS. Example of a command:
```bash
ls
```

---

## Linux Overview
**Linux** is an open-source operating system. It is based on the UNIX operating system and is known for its security and flexibility.

### Components of Linux
- **User**: The person interacting with the computer.
- **Applications**: Programs that perform specific tasks.
- **Shell**: The command-line interpreter.
- **Filesystem Hierarchy Standard (FHS)**: Organizes data on the OS.
- **Kernel**: Manages processes and memory.
- **Hardware**: Physical components of a computer.

---

### Popular Linux Distros
1. **Red Hat Enterprise Linux (RHEL)** (e.g., CentOS)
2. **Slackware** (e.g., SUSE)
3. **Debian** (e.g., Ubuntu, Kali Linux)

---

## Penetration Testing Tools
- **Metasploit**: For discovering and exploiting vulnerabilities.
- **Burp Suite**: For testing web application security.
- **John the Ripper**: For password cracking.
- **tcpdump, Wireshark, autopsy**: Digital forensic tools available in Kali Linux.

---

## Basic Linux Commands

```bash
# Display current working directory
pwd

# List files and directories
ls

# Change directories
cd <directory_name>

# Search for a string in a file
grep "<search_string>" <filename>

# Create a new directory
mkdir <directory_name>

# Create a new file
touch <filename>
```

---

## File Permissions & Ownership
In Linux, files and directories have permissions assigned to users and groups.

### Types of File Permissions
- **Read (r)**
- **Write (w)**
- **Execute (x)**

### Types of Ownership
- **User (u)**
- **Group (g)**
- **Other (o)**

Example of changing permissions using `chmod`:
```bash
# Add execute permissions for user on access.txt
chmod u+x access.txt
```

### Example File Permissions Table
| Permission | User (u) | Group (g) | Other (o) |
|------------|----------|-----------|-----------|
| Read       | ✔        | ✔         | ✔         |
| Write      | ✔        | ❌        | ❌         |
| Execute    | ✔        | ❌        | ❌         |

---

## Databases & SQL

- **Database**: Organized collection of data.
- **Relational Database**: A database structured with tables that relate to one another.
- **Primary Key**: A unique identifier for a row in a table.
- **Foreign Key**: A primary key in another table that connects the tables.

---

## Images for Reference

### Linux Directory Structure
![Linux Directory Structure](Resources/Linux-tree.jpg)

### File Permission in Linux
![File Permission In Linux](Resources/File-Permissions-Linux.png)

---
