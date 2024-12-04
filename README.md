Library Management System

The Library Management System is a C program designed to streamline the management of library books. It supports two types of users—Admins and Students—offering tailored features for managing and exploring the library catalog.

📋 Features

🛠️ Admin Functionalities

Add New Books: Easily expand the library's catalog.
Display All Books: View the complete list of books in the library.
Search for Books: Locate books by their title.
Remove Books: Delete a book by title from the catalog.
Update Book Information: Modify details like title, author, and publication year.
Sort Books: Arrange the catalog by title, author, or publication year.
Save Library Data: Export the library's current state to a file.
Load Library Data: Import library data from a file.
Count Books by Author: Display the number of books available per author.
Library Statistics: View insights like total books, earliest, and latest publication years.
Clear Library: Erase all books from the catalog.

📚 Student Functionalities

Search for Books: Find books by their title.
View All Books: Browse the library's catalog.
Count Books by Author: Check the number of books by each author.
Library Statistics: Get details like the total number of books and publication trends.

🏗️ Program Structure

Main Program: Handles user login and provides access to Admin and Student menus.
Book Structure: Represents each book with fields for title, author, and publication year.
Admin Menu: Grants access to advanced library management tools.
Student Menu: Allows students to search and view the library's catalog.

🔐 Login Credentials

Admin Login:
Email: admin
Password: admin
Student Login:

No credentials required.
🖥️ Compilation and Execution
Compile the Program:
gcc -o library_management library_management.c
Run the Program:
./library_management

📂 File Operations

Save Library: Saves the current library state to library.txt.
Load Library: Reads library data from library.txt (ensure the file exists in the program directory).
🛠️ Dependencies
Standard C libraries:
stdio.h
stdlib.h
string.h
No external libraries required.

🚀 Usage Instructions

Start the Program:
Choose your login type: Admin or Student.

Admin Login:
Enter the predefined email and password to access admin features.

Student Login:
Directly access the student menu to search and explore books.

Exit:
Return to the main menu or quit the program entirely.

🚧 Program Constraints

A maximum of 100 books can be stored.
Titles and authors have fixed maximum lengths.

💡 Future Improvements

Add user authentication for students.
Support multiple admins with unique credentials.
Expand statistics to include genres, ratings, or availability status.

✍️ Author

This Library Management System was developed as an educational project to practice C programming concepts such as file handling, arrays, and structured data.

📖 Enjoy managing your library!
