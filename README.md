# Student Management System

A Java application for managing student records in a MySQL database using JDBC.

## Features
- Add new student records
- Update existing student information
- Delete student records
- List all students in the database

## Prerequisites
- Java JDK 8 or later
- MySQL Server
- MySQL Connector/J (JDBC driver)

## Setup Instructions

1. **Database Setup**:
   ```sql
   CREATE DATABASE studentdb;
   USE studentdb;
   
   CREATE TABLE students (
       id INT AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(100) NOT NULL,
       age INT NOT NULL,
       email VARCHAR(100) NOT NULL
   );
