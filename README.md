 Simple Library Management System

A simple command-line Library Management System implemented in Python. This text-based application allows users to add, search, checkout, and return books within a library using a basic menu interface.

## Features

- **Add Book**: Add a new book to the library by entering its title, author, and ISBN.
- **Search Book**: Search for books by title or author.
- **Checkout Book**: Checkout a book using its ISBN and member ID.
- **Return Book**: Return a book using its ISBN and member ID.
- **Exit**: Exit the application.

## Prerequisites

- **Python**: Ensure Python is installed on your system. You can download it from [python.org](https://www.python.org/).

## How to Run

1. **Save the Script**: Save the script as `library_management_system.py` in your desired directory.

2. **Run the Script**:

    - Open your terminal or command prompt.
    - Navigate to the directory where `library_management_system.py` is saved.
    - Run the script using:

    ```bash
    python library_management_system.py
    ```

## Usage

The application will present a menu with the following options:

1. **Add Book**:
    - Select option `1`.
    - Enter the book title, author, and ISBN when prompted.
    - The book will be added to the library.

2. **Search Book**:
    - Select option `2`.
    - Enter the title or author to search for.
    - The application will display search results with book details.

3. **Checkout Book**:
    - Select option `3`.
    - Enter the ISBN of the book to checkout and your member ID.
    - If the book is available, it will be marked as checked out.

4. **Return Book**:
    - Select option `4`.
    - Enter the ISBN of the book to return and your member ID.
    - If the book was checked out by you, it will be marked as returned.

5. **Exit**:
    - Select option `5`.
    - The application will close.
