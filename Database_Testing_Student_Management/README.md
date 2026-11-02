# Database Testing — Student Management System

## Project Overview

This project demonstrates practical skills in database testing using SQLite and DBeaver.

The database consists of three relational tables: Students, Class_rooms, and Progress.

## Database Structure

### 1. Students

- StudentID (Primary Key)
- First_name
- Last_name
- Country
- Language
- Date_of_birth

### 2. Class_rooms

- ClassroomID (Primary Key)
- Faculty
- Num_students

### 3. Progress

- ProgressID (Primary Key)
- StudentID (Foreign Key)
- ClassroomID (Foreign Key)
- Score

## Table Relationships

The Progress table connects Students and Class_rooms through foreign keys.

## Testing Activities

- Database structure analysis
- Primary Key and Foreign Key verification
- Data retrieval using SELECT
- Data filtering and sorting
- Joining tables using JOIN
- Data validation
- Checking referential integrity

## Tools & Technologies

- SQLite
- DBeaver
- SQL

## Results

This project demonstrates practical experience in working with relational databases, writing SQL queries, analyzing table relationships, and validating data consistency.
