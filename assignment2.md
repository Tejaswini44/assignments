Domain: Library Management System
The application should handle books, authors, and borrowing records.

Entities:

Book: id, title, ISBN, author, status (available, borrowed)
Author: id, name, country, list of books
Borrowing Record: id, book, borrowing date, return date, user


Requirements:

CRUD operations for books and authors.
Borrow a book (mark it as borrowed).
Return a book (mark it as available and update the borrowing record).
Find all books by an author.
Find all borrowed books by a user.
