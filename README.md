# COS 201 Student Course Management System

## 1. Project Overview

The **COS 201 Student Course Management System** is a console-based application developed using Java. It allows users to manage course information, including course codes, course titles, and credit units.

The project demonstrates important Java programming concepts such as object-oriented programming, collections, file handling, input validation, and recursion.

## 2. Project Objectives

- To create and manage course records.
- To display all available courses.
- To search for a course using its course code.
- To calculate the total credit units of all courses.
- To save course information to a file and load it when needed.
- To prevent duplicate course codes.
- To demonstrate recursion in Java.

## 3. Features

- **Add Course:** Register a course using its code, title, and credit units.
- **List Courses:** Display all registered courses.
- **Search Course:** Find a course by its course code.
- **Calculate Credit Units:** Calculate the total credit units for all registered courses.
- **File Handling:** Save and load course records using a local file.
- **Duplicate Validation:** Prevent duplicate course codes.
- **Recursive Counting:** Demonstrate recursion when counting course records.

## 4. Technologies Used

- **Programming Language:** Java
- **Development Environment:** Visual Studio Code (VS Code)
- **Version Control:** Git
- **Repository Hosting:** GitHub

## 5. Project Structure

```text
student_management_system_JAVA/
│
├── main.java
├── Course.java
├── .gitignore
└── README.md
```

**File descriptions:**

- `main.java` — Contains the main application logic and program execution.
- `Course.java` — Represents a course and its associated information.
- `.gitignore` — Specifies files and folders Git should ignore.
- `README.md` — Documents the project and explains how to use it.

## 6. Requirements

Before running the project, ensure you have:

- Java Development Kit (JDK) installed.
- A terminal or command prompt.
- A text editor or IDE, such as Visual Studio Code.

## 7. How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/samad-source/student_management_system_JAVA.git
```

### Step 2: Open the project directory

```bash
cd student_management_system_JAVA
```

### Step 3: Compile the Java files

```bash
java main.java Course.java
```

### Step 4: Run the application

```bash
java main
```

**Note:** These commands assume the Java files have no package declaration and that `main.java` contains the application's `main` method.

## 8. Example Course Records

The following courses were used when testing the application:

| Course Code | Course Title | Credit Units |
|---|---|---:|
| COS 201 | COMPUTER PROGRAMMING | 3 |
| MTH 201 | MATHEMATICAL METHODS | 2 |
| COS 203 | DISCRETE STRUCTURES | 2 |
| | **Total** | **7** |

## 9. Concepts Demonstrated

This project demonstrates the practical use of:

1. **Classes and Objects:** Organizing course information using Java classes.
2. **Collections:** Managing multiple course records.
3. **Methods:** Separating program operations into reusable functions.
4. **Conditional Statements and Loops:** Controlling program flow and processing course records.
5. **File Handling:** Persisting course information between program runs.
6. **Input Validation:** Checking course information and preventing duplicate course codes.
7. **Recursion:** Counting course records using a recursive method.
8. **Git and GitHub:** Tracking changes and publishing source code.

## 10. Future Improvements

Possible improvements include:

- Adding student registration.
- Assigning courses to individual students.
- Updating and deleting course records.
- Creating a graphical user interface.
- Adding database support.
- Generating student course reports.

## 11. Conclusion

The COS 201 Student Course Management System provides a practical introduction to Java application development. It combines course management functionality with core programming concepts and version control practices.

## 12. Author

Developed as a COS 201 academic programming project.

**GitHub Repository:** https://github.com/samad-source/student_management_system_JAVA
