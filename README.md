# Student Management System

This is a simple console-based Student Management System implemented in C++. It provides a simple interface for maintaining a list of student records stored in a binary file. The system supports several operations such as adding a new student, displaying all students, searching for a student by ID or name, updating student data, and deleting a student.

## Code Structure

The code is structured around a `student` class and several functions that perform the operations on student records.

### Student Class

The `student` class represents a student with the following properties:

- `id`: The student's ID.
- `name`: The student's name.
- `age`: The student's age.

### Functions

The following functions are implemented:

- `addStudent()`: Adds a new student to the record.
- `readAllStudents()`: Displays all students in the record.
- `searchByID()`: Searches for a student by ID.
- `searchByName()`: Searches for a student by name.
- `updateStudent()`: Updates the data of a student.
- `deleteStudent()`: Deletes a student from the record.

## How to Run

To run the program, compile the `main.cpp` file and run the resulting executable. The program will display a menu with the available operations. Enter the number corresponding to the operation you want to perform.

```bash
g++ main.cpp -o main
./main
```

## Note

This program uses binary file operations for storing and retrieving student records. The file `student.txt` is used to store the records. If the file does not exist, the program will create it. If the file cannot be opened, the program will display an error message.
