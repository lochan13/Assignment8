# Student Management System

A Java application for managing student records with exception handling capabilities.

## Overview

This project implements a simple student management system that allows users to:
- Add new students
- Display all students
- Search for students by PRN, name, or position
- Update student information
- Delete students

The application uses custom exceptions to handle various error scenarios gracefully.

## Project Structure

```
Assignment8/
├── Main.java             # Main application entry point with menu system
├── Operations.java       # Contains core functionality for student management
├── Student.java          # Student class definition with getters and setters
└── exceptions/
    ├── CustomException.java           # Base exception class
    ├── DuplicateStudentException.java # Thrown when adding student with existing PRN
    ├── InvalidChoiceException.java    # Thrown for invalid menu selections
    ├── InvalidInputException.java     # Thrown for general input validation errors
    └── StudentNotFoundException.java  # Thrown when student lookup fails
```

## Key Features

1. **Exception Handling**: Custom exceptions provide meaningful error messages for different scenarios
2. **Student Management**: Complete CRUD operations for student records
3. **Data Validation**: Input validation to prevent invalid data entry
4. **Search Flexibility**: Multiple search options (by PRN, name, or position)

## Student Data Model

Each student record includes:
- PRN (Permanent Registration Number) - unique identifier
- Name
- Date of Birth (in YYYY-MM-DD format)
- Marks

## Usage

1. Run the `Main.java` file to start the application
2. Use the menu system to perform various operations:
   - Option 1: Add a new student
   - Option 2: Display all students
   - Option 3: Search for students using different criteria
   - Option 4: Update student information
   - Option 5: Delete a student
   - Option 6: Exit the application

## Exception Handling

- `DuplicateStudentException`: Thrown when adding a student with a PRN that already exists
- `InvalidChoiceException`: Thrown when an invalid menu option is selected
- `InvalidInputException`: Thrown when input data doesn't meet validation requirements
- `StudentNotFoundException`: Thrown when searching, updating, or deleting a non-existent student

## Author

LOCHAN PAUDEL  
PRN: 23070126170  
Branch: AIML (A3)
```

## License

This project is licensed under the MIT License.
