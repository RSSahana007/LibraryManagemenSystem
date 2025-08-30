# 📚 Library Management System (DBMS Project)

A Database Management System (DBMS) project designed to handle all activities related to a library’s books, customers, and staff.  
This project demonstrates database design, normalization, and SQL operations, built using **MySQL** with support from **MySQL Workbench** and **MySQL-CMD**.

---

## 🚀 Features

- Manage **branches, staff, and customers** efficiently.  
- Track **book details** including authors, publishers, and availability.  
- Implement **secure staff authentication system**.  
- Monitor **issued books** with proper status updates.  
- Maintain **publisher & author records**.  
- Support for **views, joins, conditional queries, and subqueries**.  
- Demonstrates **3rd Normal Form (3NF)** relational schema design.  

---

## 🏗️ Database Schema

- **Branch**: Stores library branch details and manager info.  
- **Customer**: Holds customer records and their borrowing activities.  
- **Authentication_System**: Manages login credentials for staff.  
- **Publisher**: Contains publisher details like category, price, and publish year.  
- **Author**: Tracks book authors and their works.  
- **Staff**: Information about library employees, linked with branches and login system.  
- **Book**: Book details linked with branch, publisher, and author.  
- **Updates**: Tracks updates made by staff.  
- **Issue_Status**: Records issued books, dates, and return status.  

---

## 🔑 Major Functionalities

- **Employee View** – Staff details and branch association.  
- **Customer View** – Book availability and branch information.  
- **Manager View** – Record of new staff and branch management.  
- **Issuance System** – Track issue/return status for each book.  

---

## 📊 ERD & Schema

- The project includes an **ER diagram**.  
- Final schema is normalized up to **3NF** to ensure minimal redundancy.  

---

## 📝 SQL Operations Covered

The project demonstrates wide usage of SQL, including:

- **DDL**: Creating tables with constraints & relationships.  
- **DML**: Insert, Update, Delete, Select operations.  
- **Joins**: Inner, Left, Right, and Cross joins.  
- **Views**: Multiple views for customers, staff, and books.  
- **Aggregate Functions**: COUNT, AVG, MAX, MIN.  
- **Subqueries** and **Nested queries**.  
- **User Privileges & Roles** for authentication and access control.  

---

## 🛠️ Tech Stack

- **Database**: MySQL  
- **Tools**: MySQL Workbench, MySQL CMD  
- **Language**: SQL  
