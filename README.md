# School Database using MySQL

This project demonstrates the creation of a school database in MySQL. It includes various tables for managing students, teachers, employees, courses, and more, along with relationships between them. The database is structured to handle multiple aspects of school operations, such as grading, attendance, library management, and more.

## Features

- **Tables**: The database consists of tables for `person`, `teacher`, `student`, `course`, `class`, `section`, `library_books`, `absences`, `punchments`, `medical_clinic`, and others.
- **Referential Integrity**: Various `FOREIGN KEY` constraints are used to maintain relationships between tables.
- **Support for Multiple Roles**: Different categories of employees, such as educational and non-educational, are represented in the database.
- **Data Management**: Includes tables to manage student grades, teacher assignments, borrowing of library books, and more.

## Technologies Used

- **MySQL**: For creating the database and tables.
- **SQL**: For writing queries and managing data.

## Setup Instructions

1. Install MySQL on your machine.
2. Create a new database:
   ```sql
   CREATE DATABASE school1;
   USE school1;
