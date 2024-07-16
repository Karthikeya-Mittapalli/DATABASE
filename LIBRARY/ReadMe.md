# LIBRARY DATABASE

# Overview
A Relational database designed to facilitate efficient management of books, authors, publishers, members, and book loans within a library setting. It provides a structured approach to organizing library resources and streamlining operations related to book lending and member management.

# Features
* Book Management: Add, update, and delete books, authors, publishers, and literature categories.
* Member Management: Register new members, update member information, and manage contact details.
* Loan Management: Track books that are loaned out, record loan dates, monitor return deadlines, and update return statuses.

# Database Schema
The database schema includes the following tables:

LITERATURE_CATEGORY: Stores categories of literature.
AUTHOR: Contains details about authors.
PUBLISHER: Stores information about publishers.
BOOKS: Holds data about individual books.
WRITTEN_BY: Links authors to the books they have authored.
PUBLISHING: Associates books with their publishers.
MEMBERS: Stores information about library members.
PHONENUMBER: Manages phone numbers associated with members.
BOOKITEM: Tracks unique physical copies of books.
LOANED_BOOK: Manages records of books that have been loaned to members.

# Installation
* Requirements: Ensure you have a relational database management system (RDBMS) such as MySQL, PostgreSQL, or SQLite installed.
* Setup: Execute the SQL scripts provided to create the database schema and populate it with sample data. Modify the scripts as needed to adapt to your specific environment.

# Usage
* Admin Interface: Use SQL queries or an admin interface provided to manage books, members, and loans.
* Integration: Integrate the database with a library management system for comprehensive library operations.

# Contribution
Contributions to enhance the database schema, improve functionalities, or fix issues are welcome. Fork the repository, make your changes, and submit a pull request detailing the modifications made.

# Support
For questions or assistance regarding the Library Management System, please contact Karthikeya Mittapalli.
