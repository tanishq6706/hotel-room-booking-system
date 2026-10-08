# Leafline Library Management System

A full-stack web application built with HTML, CSS, JavaScript, Python Flask, and SQLite.

## Run the application

1. Open a terminal in the project folder.
2. Run `python app.py`.
3. Open `http://127.0.0.1:5000` in a browser.

Flask is already installed in this workspace. On another computer, first run `pip install -r requirements.txt`.

If Node.js is installed, the equivalent frontend-tooling command is `npm start`.

## Included features

- Add books with title, author, ISBN, and category validation
- View the complete collection dynamically without page reloads
- Search by title, author, ISBN, or category
- Filter books by Available and Issued status
- Issue a book to a member using their name and email
- Return an issued book
- Prevent a book from being issued twice
- Delete a book record
- SQLite tables for both books and members
- Live collection statistics

## Testing completed

The application was tested for add, search, duplicate ISBN prevention, issue, double-issue prevention, return, invalid return prevention, delete, and deletion of a missing record.
