# Library Management System for Basilan State College

This project is a **Library Management System** developed specifically for Basilan State College. It aims to streamline library operations such as managing books, users, borrowing, returning, reservations, and fines. Built with Java in NetBeans IDE 12.2 and utilizing MySQL via XAMPP, this system offers an easy-to-use interface coupled with robust backend functionality.

---

## Features

- **User Roles:** Different access levels for Librarians and Students.
- **Book Management:** Add, update, delete, and search books.
- **Borrow and Return:** Issue books to users and process returns with due date tracking.
- **Reservations:** Reserve books that are currently borrowed.
- **Fines Management:** Calculate and manage overdue fines.
- **Reports:** Generate reports on books, users, borrowing history, overdue items, and more.

---

## Technologies Used

- **Java** (NetBeans IDE 12.2)
- **MySQL** (via XAMPP)
- **JDBC** for database connectivity
- **JCalendar** for jSpinField

---

## Setup Instructions

Follow these steps to run the project locally:

### 1. Install Necessary Software
- [NetBeans IDE 12.2](https://netbeans.apache.org/download/index.html)
- [XAMPP](https://www.apachefriends.org/index.html)

### 2. Configure MySQL Database
- Start the MySQL server via XAMPP Control Panel.
- Import the database schema:
  - Locate the `library_basc_db.sql` file in the project folder.
  - Open phpMyAdmin at `http://localhost/phpmyadmin`.
  - Create a new database (e.g., `library_basc_db`).
  - Import the `database.sql` file into this database.

### 3. Setup the Java Project
- Open NetBeans IDE 12.2.
- Import the project folder.
- Update the database connection settings in your Java code (`Connection.java` or equivalent) to match your database configuration:
  - Hostname: `localhost`
  - Port: `3306`
  - Database name: `library_basc_db`
  - Username: `root`
  - Password: *(leave blank or as set in XAMPP)*

### 4. Run the Application
- Build and run the project within NetBeans.
- The system should launch, allowing you to log in as a librarian or student and start managing the library.

---
## Developer

- **Jaymar Maruji**

---

## License

This project is for educational purposes. Feel free to use, modify, and distribute it as needed.

---

## Acknowledgments

- Built with Java and MySQL.
- Inspired by the need for efficient library management in educational institutions.

---

## Contact

For questions or contributions, please contact: jaymmaruji@gmail.com or Jaymar Maruji on Facebook

---

**Happy coding!**"# Library-Management-System-for-Basilan-State-College" 
