# Flask Library Management System

This is a Flask-based web application that allows users to manage a library of books. Users can add, delete, and view books, with the data stored in a JSON file.

## Features

- Add new books to the library.
- Delete books from the library by title.
- View all books in the library.
- Persistent data storage using a JSON file.

---

## 📂 Project Structure
      
        library-management-system/
        ├── static/
        │   ├── css/
        │   │   └── style.css
        │   ├── js/
        │   │   └── app.js
        ├── templates/
        │   ├── index.html
        │   └── base.html
        ├── app.py
        ├── requirements.txt
        ├── README.md

---

## Requirements

- Python 3.x
- Flask

Install required packages using:
```bash
pip install flask
{
    "title": "Book Title",
    "author": "Author Name"
}
{
    "message": "Book 'Book Title' by Author Name added successfully."
}

[
    {
        "Title": "Book Title 1",
        "Author": "Author Name 1"
    },
    {
        "Title": "Book Title 2",
        "Author": "Author Name 2"
    }
]

