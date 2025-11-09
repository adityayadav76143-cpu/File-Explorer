File Explorer – Capstone Project

**Project Objective**

The objective of this project is to develop a console-based File Explorer using C++17 that allows users to interact with the operating system’s filesystem.
The application provides basic file management functionalities such as navigating directories, creating and deleting files, copying, renaming, and viewing detailed file information.
This project demonstrates the practical application of C++ filesystem operations and reinforces key concepts from the Linux Operating System module.

**Project Description**

The File Explorer operates entirely from the terminal, providing users with simple, text-based commands to perform file operations.
It utilizes the <filesystem> library introduced in C++17 to handle all file and directory interactions.
The project focuses on offering a minimal yet functional interface that enables users to explore folders, manage files, and retrieve file metadata like size, type, and modification date.

**Features**

This project supports the following functionalities:
Viewing files and directories in the current location
Navigating through folders using cd and back commands
Creating, deleting, renaming, and copying files
Searching files recursively by name
Viewing detailed file information including size, permissions, and last modified time

**Commands**

The File Explorer accepts simple text commands:
list, cd <folder>, back, create <file>, delete <file>, rename <old> <new>, copy <src> <dest>, search <name>, info <file>, exit

**Example Execution**

> list
main.cpp
README.md
test.txt

> create data.txt
File created: data.txt

> info data.txt
Name: data.txt
Type: File
Size: 0 bytes
Last Modified: Sat Nov 08 22:41:18 2025
Permissions: rw-rw-rw-

**Technologies Used**

The project is implemented using C++17 and primarily makes use of:
<filesystem> for file and directory management
<fstream> for file input and output operations
<chrono> for handling time attributes
The development environment used was Visual Studio Code with MinGW (g++) compiler on Windows. The program is also compatible with Linux and WSL.

**Author**

Aditya Yadav
Capstone Project – Linux OS Track
Department of Computer Science and Engineering

