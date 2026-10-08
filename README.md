# SQL Lab 1 – Banking Database Setup & Table Structure

## 📌 Overview

This lab introduces the fundamentals of **MySQL and SQL databases** by setting up a banking database environment and exploring the structure of banking tables.

The project is based on a digital banking system called **BankingDB**, designed to store and manage customer, account, and transaction-related information.

---

## 🎯 Objectives

- Install and configure MySQL
- Connect to MySQL using MySQL Workbench
- Create a banking database
- Create banking tables
- Understand SQL data types
- Explore table structures
- Understand rows and columns
- Prepare the database environment for future SQL operations

---

## 🏦 Business Scenario

The digital banking company wants to develop a **Banking Management Database System**.

The system will eventually support:

- Customer information
- Bank account details
- Transactions and payments
- Organized banking records
- Database and table management

---

## 🛠️ Tasks Completed

### 1. MySQL Installation
- Installed MySQL Server
- Installed MySQL Workbench
- Configured the MySQL root account
- Connected to the local MySQL instance

### 2. Database Creation

Created the banking database using:

```sql
CREATE DATABASE BankingDB;
USE BankingDB;
```

Verified available databases using:

```sql
SHOW DATABASES;
```

### 3. Customers Table

Created the `Customers` table to store customer information.

```sql
CREATE TABLE Customers (
    CustomerID INT PRIMARY KEY,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    Email VARCHAR(100),
    Phone VARCHAR(15),
    AccountCreationDate DATE
);
```

### 4. Explore Table Structure

Used the `DESCRIBE` command to understand the table structure:

```sql
DESCRIBE Customers;
```

This helps identify:

- Column names
- Data types
- Primary keys
- NULL restrictions
- Default values
- Additional properties

### 5. Understanding Rows and Columns

Learned the basic structure of relational databases:

**Column:** Represents a specific type of information.

Example:

```text
CustomerID | FirstName | LastName | Email
```

**Row:** Represents one complete record stored in the table.

Example:

```text
101 | Rahul | Sharma | rahul@example.com
```

---

## 🧩 SQL Concepts Learned

| Concept | Description |
|---|---|
| `CREATE DATABASE` | Creates a new database |
| `USE` | Selects a database |
| `SHOW DATABASES` | Displays available databases |
| `CREATE TABLE` | Creates a new table |
| `DESCRIBE` | Shows table structure |
| `INT` | Stores whole numbers |
| `VARCHAR` | Stores text |
| `DATE` | Stores dates |
| `PRIMARY KEY` | Uniquely identifies records |

---

## 🗄️ Database Structure

```text
BankingDB
│
└── Customers
    ├── CustomerID
    ├── FirstName
    ├── LastName
    ├── Email
    ├── Phone
    └── AccountCreationDate
```

---

## 🔧 Tools Used

- MySQL Server
- MySQL Workbench
- SQL
- Git
- GitHub

---

## 📚 Key Learning

Through this lab, I learned how to:

- Set up a MySQL database environment
- Create and select databases
- Create tables using SQL
- Define columns with appropriate data types
- Use primary keys
- Inspect table structures
- Understand the difference between rows and columns
- Prepare a database for further development

---

## 🚀 Next Steps

The next stage will focus on **Crafting SQL Databases (DDL)**, including:

- Database relationships
- Entity Relationship Diagrams (ERD)
- Normalization and Denormalization
- DDL commands
- SQL constraints

---

## ✅ Status

**SQL Lab 1 completed and uploaded to GitHub.**
