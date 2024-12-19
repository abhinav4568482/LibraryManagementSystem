# LibraryManagementSystem
Project Overview
The Library Management System is a console-based application developed in C++ that facilitates efficient management of library resources. It enables students to register or log in to access library data, while admins can manage books and student accounts. Key functionalities include adding, editing, and viewing books, issuing books to students, and handling fines.

Key Features
User Authentication
Login functionality for both admins and students, secured with passwords.
Admin Functions
Add Books: Admins can add new books to the library database.
Edit Book Details: Modify the title or author of a book using its ISBN number.
View Book Status: Access the list of books and their availability.
Manage Students: View registered students, sorted by roll number, and check their account balances.
Student Functions
Account Creation: New students can register by providing their roll number, name, and an initial deposit.
Balance Management: Students can view and deposit money into their accounts.
Issue Books: Borrow books for a 10-day period at a cost of $2, with late return fines applied.
Data Storage
Utilizes 2D arrays for managing student and book details.
Initially stores data for 15 books and supports up to 20 student accounts.
Each student record includes their roll number, balance, and first name.
Implementation Details
Implemented using C++ without classes, pointers, or structures.
Relies on functions, loops, if-else statements, and switch operators.
The main() function handles user input, presents options, and calls relevant functions based on user selection.
Designed to run continuously in a loop until the user opts to exit.
This project is ideal for students who have completed a Programming Fundamentals course and wish to showcase their skills in C++ without delving into advanced concepts. It provides a strong base for learning and future improvement in software development.

