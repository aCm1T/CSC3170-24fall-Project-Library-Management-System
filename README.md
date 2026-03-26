# Athena Library Management System

![Athena LMS](https://img.shields.io/badge/Language-Python-blue.svg)
![GUI](https://img.shields.io/badge/GUI-Tkinter-yellow.svg)
![Database](https://img.shields.io/badge/Database-SQLite3-green.svg)

**Athena Library Management System** is a comprehensive, feature-rich desktop application built with Python and Tkinter. It offers a streamlined, intuitive interface for managing library operations and analyzing data, designed for both patrons and library administrators.

## Features

### 🛡️ Role-Based Access Control
- **User**: Search the catalog, borrow/return books, renew loans, reserve unavailable books, and view personal borrowing history.
- **Admin**: Manage book inventory (Add/Edit), oversee lending records, and access powerful data analytics.
- **IT Admin**: Comprehensive user management including creating, updating, and deleting user accounts, as well as role assignment.

### 📚 Catalog & Operations
- **Advanced Search**: Filter books by Title, Author, or ISBN.
- **Reservation System**: Get notified and automatically prompt to borrow when a reserved book becomes available.
- **Smart Reminders**: Automatic notifications for upcoming due dates (7 days advance).
- **Borrowing History**: Track all current and past lending records.

### 📊 Data Analytics & Reporting
Integrated with `pandas` and `matplotlib` to provide insightful visualizations:
- **Most Borrowed Books**: Identify the library's most popular titles.
- **Borrowing Trends**: Visualize loan activities over time.
- **Top Borrowers**: Track the most active users.
- **Inventory Analysis**: Quickly spot low-stock books that need replenishment.

## Installation & Setup

1. **Clone or Download the Repository**
2. **Install Dependencies**:
   Ensure you have Python 3.7+ installed. Install the required libraries via pip:
   ```bash
   pip install pandas matplotlib
   ```
3. **Run the Application**:
   ```bash
   python Main.py
   ```

4. **Testing Accounts** (Username / Password):
   - Admin: `admin` / `admin123`
   - IT Admin: `itadmin` / `itadmin123`
   - User: `user1` / `user123`

## Database Initialization
Upon first launch, the system automatically initializes the necessary SQLite3 database (`library.db`) and creates tables for Users, Books, BorrowedBooks, and Reservations, along with populating sample book data.

## License
MIT License
