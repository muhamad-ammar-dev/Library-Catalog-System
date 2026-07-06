# 📚 Library Catalog System - Python Project

## 🎯 Project Overview

**Library Catalog System** is a Python command-line application that provides a comprehensive solution for managing a library's book collection. This system allows librarians to track books, manage check-ins/check-outs, and maintain an organized catalog with real-time availability status.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Library Management](https://img.shields.io/badge/Library-Management-green)
![No Database](https://img.shields.io/badge/Storage-In--Memory-yellow)
![License](https://img.shields.io/badge/License-MIT-orange)

## ✨ Key Features

- **📖 Add Books**: Easily add new books to the catalog with ISBN, title, and author information
- **🔍 Check Out Books**: Mark books as borrowed and track their availability status
- **📥 Check In Books**: Update the system when books are returned
- **📋 List Books**: View the complete catalog with current availability status
- **🔄 Interactive Menu**: User-friendly command-line interface with clear navigation
- **🧹 Clean Interface**: Terminal clearing for better user experience

## 🏗️ System Architecture

The application uses a dictionary-based in-memory storage system with the following structure:

```python
library_catalog = {
    "ISBN-12345": {
        "title": "Book Title",
        "author": "Author Name", 
        "available": True/False
    }
}
```

## 🛠️ Technologies Used

- **Python 3** - Core programming language
- **OS Module** - For terminal clearing operations
- **Dictionary Data Structure** - For efficient book storage and retrieval
- **Control Structures** - While loops and conditional statements for workflow management

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed on your system

### Installation & Execution

1. Download or clone the project files
2. Navigate to the project directory
3. Run the application:
   ```bash
   python library_catalog.py
   ```

### How to Use

1. **Adding Books**: Select option 1 from the menu and enter the ISBN, title, and author
2. **Checking Out Books**: Select option 2 and enter the ISBN of the book to borrow
3. **Checking In Books**: Select option 3 and enter the ISBN of the returned book
4. **Viewing Catalog**: Select option 4 to see all books and their availability status
5. **Exiting**: Select option 5 to exit the application

## 💻 Code Structure

The application is organized into several functions:

- `clear_terminal()`: Clears the console for better readability
- `add_book()`: Handles adding new books to the catalog
- `check_out_book()`: Processes book check-outs
- `check_in_book()`: Processes book returns
- `list_books()`: Displays all books in the catalog

Main program loop provides a continuous menu interface until the user chooses to exit.

## 🌟 Technical Highlights

- **Input Validation**: Basic validation for menu options and continuation prompts
- **User Experience**: Clean terminal interface with appropriate clearing between operations
- **Data Integrity**: Prevents checking out already borrowed books and checking in available books
- **Memory Efficiency**: Uses dictionary data structure for O(1) access time

## 📊 Sample Data Structure

```python
{
    "978-0451524935": {
        "title": "1984",
        "author": "George Orwell",
        "available": True
    },
    "978-0141439518": {
        "title": "Pride and Prejudice", 
        "author": "Jane Austen",
        "available": False
    }
}
```

## 🔮 Potential Enhancements

- **Data Persistence**: Add file storage to save catalog between sessions
- **Advanced Search**: Implement search by title, author, or ISBN
- **User Management**: Add patron accounts and borrowing history
- **Due Dates**: Implement due date tracking and overdue notifications
- **GUI Interface**: Develop a graphical user interface
- **Database Integration**: Replace in-memory storage with a proper database system

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or suggestions about this project:

- ✉️ **Email**: [muhamad.ammar09001@gmail.com](mailto:muhamad.ammar09001@gmail.com)  
- 🔗 **LinkedIn**: [Muhamad Ammar](https://www.linkedin.com/in/muhamad-ammar-18b427306)
- 🔗 **Portfolio**: [https://muhamad-ammar-dev.github.io/My-Portfolio-DevMA/](https://muhamad-ammar-dev.github.io/My-Portfolio-DevMA/)

---

📚 **Happy reading and cataloging!** 📖
