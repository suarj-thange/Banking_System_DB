# 🏦 Banking System Database

A relational database project designed to manage and organize core banking operations such as customers, accounts, transactions, branches, and other banking-related activities.

This project demonstrates how **SQL and relational database concepts** can be used to build a structured banking system capable of storing customer information, managing accounts, recording transactions, and maintaining relationships between different banking entities.

---

## 📌 Project Overview

The **Banking System Database** is a MySQL-based database project that models the major components of a banking environment.

The database is designed with a relational structure to ensure that information is organized, connected, and easily accessible for analysis and operational queries.

The project includes:

* Database and table creation
* Primary and foreign key relationships
* Entity Relationship (ER) modeling
* Customer and account management
* Banking transaction management
* Relational data organization
* SQL queries for retrieving and analyzing banking information

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Design a structured relational database for banking operations
* Store and manage customer and banking information efficiently
* Establish relationships between different banking entities
* Maintain data integrity using keys and constraints
* Perform SQL queries to retrieve meaningful information
* Demonstrate practical implementation of database management concepts

---

## 🗂️ Database Design

The database follows a relational data model where different entities are connected through primary and foreign keys.

### Main Entities

The banking system is organized around entities such as:

* **Customers** – Stores customer-related information
* **Accounts** – Maintains customer bank account details
* **Transactions** – Records financial transactions
* **Branches** – Represents banking branches and their information

These entities are connected to maintain relationships between customers, their accounts, transactions, and branches.

---

## 🔗 Entity Relationship Diagram

The project includes an ER diagram created using **MySQL Workbench** to visualize the database structure and relationships between entities.

### ER Diagram

The ER diagram represents:

* Entities
* Attributes
* Primary Keys
* Foreign Keys
* Relationships between tables

> The ER diagram file is available in the repository as `ER_DIAGRAM.mwb`.

---

## 🛠️ Technologies Used

| Technology                    | Purpose                                      |
| ----------------------------- | -------------------------------------------- |
| **MySQL**                     | Database management                          |
| **SQL**                       | Database creation, manipulation and querying |
| **MySQL Workbench**           | Database design and ER diagram               |
| **Relational Database Model** | Organizing interconnected banking data       |

---

## 💾 Project Structure

```text
Banking_System_DB/
│
├── Banking_SystemDB.sql
│   └── Database structure, tables, constraints and SQL queries
│
├── ER_DIAGRAM.mwb
│   └── MySQL Workbench ER diagram
│
├── ER_DIAGRAM.mwb.bak
│   └── Backup of the ER diagram
│
└── 1NPDPRO5.DOC
    └── Supporting project documentation
```

---

## ⚙️ Key SQL Concepts Demonstrated

This project applies several important SQL and database concepts, including:

* `CREATE DATABASE`
* `CREATE TABLE`
* `ALTER TABLE`
* Primary Keys
* Foreign Keys
* Constraints
* `INSERT`
* `UPDATE`
* `DELETE`
* `SELECT`
* `WHERE`
* `ORDER BY`
* `GROUP BY`
* Aggregate Functions
* Joins
* Subqueries
* Data filtering
* Data manipulation
* Relational database design

---

## 📊 Example Business Questions

The database can be used to answer practical banking-related questions such as:

* Which customers have bank accounts?
* Which accounts belong to a particular customer?
* What transactions have been performed on an account?
* What is the transaction history of a customer?
* Which branches manage the most accounts?
* What are the different types of accounts?
* Which customers have performed transactions?
* What is the total transaction amount?
* How can customer and account information be combined using SQL joins?

These queries demonstrate how a database can support **banking operations and business analysis**.

---

## 🔐 Data Integrity

Data integrity is maintained through relational database constraints such as:

* **Primary Keys** – Uniquely identify records
* **Foreign Keys** – Maintain relationships between tables
* **Constraints** – Help maintain valid and consistent data
* **Relationships** – Prevent unnecessary duplication and improve database structure

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/suarj-thange/Banking_System_DB.git
```

### 2. Open MySQL Workbench

Open **MySQL Workbench** and connect to your MySQL server.

### 3. Open the SQL File

Open:

```text
Banking_SystemDB.sql
```

### 4. Execute the Script

Run the SQL script to create the database, tables, relationships, and required data.

### 5. Explore the Database

After execution, you can run SQL queries to explore customer, account, transaction, and banking information.

---

## 📈 Project Highlights

### Database Design

Designed a relational database structure representing real-world banking entities and their relationships.

### Data Management

Created tables and relationships to organize banking information efficiently.

### SQL Analysis

Used SQL queries to retrieve, filter, combine, and analyze information stored in the database.

### ER Modeling

Created an Entity Relationship Diagram to visually represent the database architecture.

### Business Perspective

The project focuses on how a banking database can support real-world operational and analytical requirements rather than only demonstrating individual SQL commands.

---

## 💡 What I Learned

Through this project, I gained practical experience in:

* Designing relational databases
* Understanding database normalization and relationships
* Creating primary and foreign key relationships
* Writing SQL queries
* Working with multiple related tables
* Using MySQL Workbench
* Creating ER diagrams
* Thinking about database design from a business perspective

---

## 🔮 Future Improvements

The project can be further expanded by adding:

* Stored Procedures
* Triggers
* Views
* User authentication
* Loan management
* Credit card management
* ATM transaction management
* Interest calculation
* Monthly account statements
* Fraud transaction detection
* Banking analytics dashboard
* Power BI integration

---

## 👨‍💻 Author

**Suraj Thange**

BE Computer Engineering | Data Science & Data Analytics

Interested in **Data Analytics, SQL, Python, Excel, Power BI and Data Science**.

### 🔗 GitHub Repository

[Banking System Database](https://github.com/suarj-thange/Banking_System_DB)

---

## ⭐ Project Purpose

This project was developed as a practical implementation of **SQL and relational database concepts**, with a focus on designing a structured database that represents real-world banking operations.

If you find this project useful, feel free to explore the repository and the SQL implementation.
