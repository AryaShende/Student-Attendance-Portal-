# Student-Attendance-Portal-
Project Overview

This project is an Attendance Tracking System designed to help professors manage student attendance effectively. The system allows professors to mark attendance, manage student records, and generate attendance reports. It is built using modern web technologies, styled with Bootstrap, and powered by SQLite as the database.

Features

1. Dashboard

Provides an overview of key statistics like:

Total Students

Attendance marked today

Monthly attendance percentage.

Centralized navigation for various features.

2. Add Student

Professors can add new students to the database.

Fields include:

Student Name

Roll Number

Division

3. Mark Attendance

Professors can mark attendance by selecting a division and date.

Simple and user-friendly form for attendance input.

4. Manage Students

Options to add or remove students from the system.

View and edit student records in a tabular format.

5. Generate Attendance Reports

Generate monthly attendance reports for selected divisions.

Export and view reports in a user-friendly format.

Technology Stack

Frontend: HTML5, CSS3, Bootstrap 5

Backend Framework: PHP Laravel or Python Flask (for dynamic functionality)

Database: SQLite

Scripting: JavaScript for dynamic content display and interactions

Folder Structure

project-folder/
├── index.html                 # Main dashboard page
├── add-student.html           # Page to add student details
├── mark-attendance.html       # Page to mark attendance
├── manage-students.html       # Page to manage student records
├── generate-report.html       # Page to generate reports
├── assets/
│   ├── css/                   # Custom CSS files
│   └── js/                    # JavaScript files
└── database/
    └── attendance.db          # SQLite database file

How to Run the Project

Prerequisites

Install a web server like XAMPP or WAMP for PHP, or ensure Python Flask is set up.

SQLite installed on the system.

Steps

Clone or download the project folder.

Place the project in the web server's root directory.

Start the server.

Open index.html in your browser.
