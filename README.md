# Student Data Handling Program

This project is an assignment for the "Principles of Computer Science" module. The program performs basic manipulation of student data from a CSV file and outputs the modified data to a new CSV file.

## Table of Contents

- [Purpose](#purpose)
- [Features](#features)
- [Program Structure](#program-structure)
- [User Guide](#user-guide)
- [Testing](#testing)
- [Limitations](#limitations)
- [Author](#author)

## Purpose

The program is designed to:
- Read student data from a CSV file.
- Manipulate the data by adding, removing, or displaying student records.
- Perform calculations on student data (such as average marks).
- Sort and output the manipulated data to a new CSV file.

## Features

- **Inheritance**: The program uses inheritance to create a base `Student` class and derived classes `Student_Course` and `Student_Research`.
- **Polymorphism**: Method overriding is used to provide specific implementations for different types of students.
- **Dynamic Binding**: The program dynamically determines which method implementation to use at runtime.
- **Sorting Algorithm**: A bubble sort algorithm is implemented to sort the students by their ID in ascending order.
- **CSV Handling**: The program reads and writes student data to and from CSV files using the `java.io` package.

## Program Structure

The program consists of the following main classes:
- `Student`: The base class for all student types.
- `Student_Course` and `Student_Research`: Derived classes for coursework and research students.
- `Unit`, `Unit_Course`, and `Research`: Classes to handle specific details related to student courses and research.
- `Client`: The main class containing methods for interacting with the user and managing student data.

## User Guide

1. **Load the Program**: Ensure all program files and the CSV file are located correctly.
2. **Run the Program**: Click "Run" in your IDE.
3. **Options**:
   - **Option 1**: Quit the program.
   - **Option 2**: Import data from the CSV file (`student.csv`).
   - **Option 3**: Delete a student by ID.
   - **Option 4**: Display all student information.
   - **Option 5**: Calculate average marks and determine the number of students above and below it.
   - **Option 6**: Report grades for a student by ID.
   - **Option 7**: Sort students by ID in ascending order.
   - **Option 8**: Output the sorted data to `programOutput.csv`.

## Testing

The program includes various tests, such as:
- Testing the equality of two students.
- Verifying grade reporting.
- Checking calculations for marks and grades.
- Testing the addition and removal of student records.

## Limitations

- Handles only two types of classes: coursework and research.
- Lacks data security features.
- Designed to run in an IDE environment, not as a standalone application.

## Author

- **Name**: Yin Zhanpeng
- **Student ID**: *****
- **Date**: March 27, 2023
