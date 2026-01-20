##File-Based Student Record Management System in C
Overview

This project is a system-level application developed in C that manages structured student data using file input/output operations.
The application demonstrates efficient memory usage, structured data organization, and low-level file handling techniques to store and manipulate persistent data.

Features

Add new student records

Display all stored student records

Search for a student by ID

Delete a student record

Persistent data storage using binary files

Technologies Used

Programming Language: C

File Handling: Binary file I/O

Compiler: GCC

Data Structure

Student data is stored using a structure:

struct Student {
    int id;
    char name[50];
    int age;
    float marks;
};

File Handling Approach

Uses binary files (students.dat) for efficient storage

File operations implemented using:

fopen()

fread()

fwrite()

fclose()

Temporary file method used for safe deletion of records

How to Compile and Run
Compile
gcc student_management.c -o student_management

Run
./student_management

Project Structure
student_management.c
students.dat
README.md

Functional Modules

addStudent() – Adds a new record to the file

displayStudents() – Reads and displays all records

searchStudent() – Searches for a record by student ID

deleteStudent() – Removes a record using a temporary file

Key Concepts Demonstrated

System-level programming in C

Binary file handling

Structured data management

Memory-efficient design

CRUD operations using files

Use Cases

Academic mini-project for File Handling in C

Demonstration of persistent storage without databases

Understanding low-level data management

Future Enhancements

Update student records

Password-protected access

Sorting records by marks or name

Migration to system calls (open, read, write)

Author

K. Mahaveer
