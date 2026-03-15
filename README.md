# Library_Management_System
    .A Library Management System (LMS) is a digital solution designed to streamline and automate the daily operations of a library.
    .Moving away from traditional, error-prone paper ledgers, an LMS provides a centralized database to track physical and digital assets, manage member profiles, and monitor the flow of borrowed materials


# 📚 Library Management System

A fully-featured, desktop-based Library Management System built with Python. This application provides a graphical user interface (GUI) to manage library inventory, track book issues/returns, and export library data, all backed by a MySQL database.

## ✨ Features

* **Inventory Management:** Add, view, and manage books in the library catalog.
* **Transaction Tracking:** Issue books to students/members and process returns.
* **History & Logs:** Keep a comprehensive history of all borrowed and returned items.
* **Data Export:** Easily export library data (All Books, Issued Books, History) to external files using Pandas.
* **Graphical Interface:** An intuitive, interactive UI built with Tkinter.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **GUI Framework:** Tkinter
* **Database:** MySQL (`mysql.connector`)
* **Data Manipulation:** Pandas
* **Image Processing:** Pillow (PIL)

## 📋 Prerequisites

Before running this project, ensure you have the following installed on your system:

1. **Python 3.x** (Download from [python.org](https://www.python.org/))
2. **MySQL Server** (Running locally or remotely)
3. Required Python libraries. You can install them via pip:

```bash
pip install mysql-connector-python pandas Pillow
```

.*Database Setup:

Ensure your MySQL server is running.

You may not need to create a base database in MySQL before running the script (update the connection credentials in the Python file if necessary).

Note: The application is designed to automatically generate the required tables (all_books, issue_b, his_b, iss_b_t) upon initialization.


Run the Application:

```bash
python "Library Management System.py"

```

📂 Database Structure
The application uses the following core tables to manage data:

.all_books: Stores details of every book (ID, Name, Author, Price, ISBN, etc.).

.issue_b: Tracks currently issued books and the associated student/member details.

.his_b: Maintains a historical log of all past transactions (issue and return dates).









```bash
.Clone the repository:
git clone [https://github.com/yourusername/library-management-system.git](https://https://github.com/aakulalokesh2007-tech/Library_Management_System.git)



