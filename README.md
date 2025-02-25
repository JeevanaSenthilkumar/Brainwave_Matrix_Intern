📚 Library Management System (SQL)
📝 Project Description
This project is a relational database system designed for managing a library's book inventory, member details, and book borrowing records. The database ensures smooth operations by tracking book availability, member registrations, and loan transactions.

Built using MySQL, this database allows efficient storage and retrieval of information, ensuring seamless library management.

🚀 Features
✔ Books Table – Stores book details like title, author, ISBN, genre, and availability.
✔ Members Table – Stores member details like name, email, phone, and join date.
✔ Borrowing Table – Tracks book borrowing and returns with automatic updates.
✔ Data Integrity – Uses FOREIGN KEYS to maintain relationships.
✔ Triggers for Automation – Updates book availability when borrowed/returned.
✔ Queries for Analysis – Find borrowed books, overdue returns, and available books.

🏗️ Database Structure
📌 Tables:
1️⃣ Books – Stores book details and availability status.
2️⃣ Members – Stores registered library members.
3️⃣ Borrowing – Tracks transactions when a book is borrowed or returned.

📌 Relationships:
Members ↔ Borrowing: Member_ID (Foreign Key)
Books ↔ Borrowing: Book_ID (Foreign Key)
📂 SQL Scripts
library_db.sql – Full SQL script for creating and populating the database.
queries.sql – Queries for managing and analyzing data.
triggers.sql – SQL Triggers for automatic updates.
🛠️ Technologies Used
Database: MySQL
SQL Concepts: CRUD operations, Joins, Triggers, Constraints

📢 Future Improvements
🔹 Implement a User Interface (UI) with Python/Java for easier access.
🔹 Add Fine Calculation System for overdue books.
🔹 Develop a search functionality for books.
