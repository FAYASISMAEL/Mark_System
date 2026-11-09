
# Student Marks Analyzer

## Project Description

Student Marks Analyzer is a console-based mini project developed using C++. The program allows users to enter student marks and performs basic analysis to generate a marks report.

It uses arrays, functions, loops, and conditional statements to calculate and display student performance.

## Features

- Accepts the number of students (1–100).
- Reads and stores marks using an array.
- Calculates the total marks.
- Calculates the average marks.
- Finds the highest mark.
- Finds the lowest mark.
- Counts the number of passed students.
- Counts the number of failed students.
- Displays a complete student marks report.
- Allows users to analyse another set of marks.

## Concepts Used

The following C++ programming concepts are used in this project:

- Variables and Data Types
- Arrays
- Functions
- Function Declaration and Definition
- Function Parameters and Return Types
- For Loop
- Do-While Loop
- If-Else Statements
- Type Casting
- Input and Output Operations

## Functions Used

| Function | Description |
|----------|-------------|
| `readMarks()` | Reads and stores student marks in an array. |
| `findTotal()` | Calculates the total marks of all students. |
| `findAverage()` | Calculates the average marks. |
| `findHighest()` | Finds the highest mark. |
| `findLowest()` | Finds the lowest mark. |
| `countPassed()` | Counts students who scored 40 or above. |
| `printReport()` | Displays the complete marks report. |

## Passing Criteria

- Maximum mark: 100
- Minimum mark: 0
- Passing mark: 40
- Students scoring 40 or above are considered passed.
- Students scoring below 40 are considered failed.

## Project Structure

```text
Mini_Project/
│
├── main.cpp
│
└── README.md
```

## Requirements

- C++ Compiler (GCC / MinGW)
- Visual Studio Code
- Windows Operating System (for the commands below)

## How to Compile and Run

### Step 1: Open the project folder in VS Code.

### Step 2: Open the terminal.

### Step 3: Compile the program.

```bash
g++ main.cpp -o marks_analyzer.exe
```

### Step 4: Execute the program.

```powershell
.\marks_analyzer.exe
```

## Sample Output

```text
Enter number of students (1-100): 5

Enter marks of 5 students:
Student 1: 85
Student 2: 35
Student 3: 90
Student 4: 65
Student 5: 25

========== STUDENT MARKS REPORT ==========
Number of students : 5
Total marks        : 300
Average marks      : 60
Highest mark       : 90
Lowest mark        : 25
Passed             : 3
Failed             : 2
==========================================

Do you want to analyse another set of marks? (y/n): n

Thank you! Program ended.
```

## Known Limitations

- Supports a maximum of 100 students.
- Marks are expected to be between 0 and 100, but input validation is not currently implemented.
- The passing mark is fixed at 40.
- Student names are not stored.
- Results are not saved permanently.
- The program uses a console-based interface.

## Future Improvements

- Add student names and roll numbers.
- Add input validation for marks.
- Store student records in files.
- Generate individual student performance reports.
- Add a graphical user interface.

## Project Information

**Project Name:** Student Marks Analyzer

**Programming Language:** C++

**Project Type:** Mini Project

**Developed As:** C++ Programming Module Assignment
