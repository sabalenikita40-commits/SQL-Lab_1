# Banking Database Management System – SQL Lab

## 📌 Project Overview

This project demonstrates the creation and basic management of a banking database using **MySQL**.

The database is created for a digital banking system and contains tables for managing customer, account, transaction, branch assignment, and loan-related information.

The project focuses on practicing SQL commands such as `CREATE TABLE`, `SELECT`, and `ALTER TABLE`.

## 🏦 Database

**Database Name:** `bank`

The following tables have been created:

- Accounts
- Transaction
- AccountBranches
- Loans
- Customer

## 📊 Tables Created

### 1. Accounts

The `accounts` table stores basic account information.

**Columns:**
- Account_Id
- Account_Type
- Balance

### 2. Transaction

The `Transaction` table stores transaction-related information.

**Columns:**
- Transaction_Id
- Transaction_Date
- Amount
- Transaction_Type

### 3. AccountBranches

The `AccountBranches` table stores account branch assignment information.

**Column:**
- Assignment_Date

### 4. Loans

The `Loans` table stores basic loan information.

**Columns:**
- Loan_ID
- Loan_Amount
- Interest_Rate
- Start_Date
- End_Date

### 5. Customer

The `Customer` table stores customer information.

**Columns:**
- Customer_ID
- First_Name
- Last_Name
- Email
- Phone
- DateOfBirth

## 🔧 Table Alteration

The `Customer` table was modified using the `ALTER TABLE` command.

### Add Date of Birth Column

```sql
ALTER TABLE Customer
ADD COLUMN DateOfBirth DATE;

Modify Phone Column

The Phone column was modified from VARCHAR(15) to VARCHAR(20).

ALTER TABLE Customer
MODIFY COLUMN Phone VARCHAR(20);
🔍 Data Retrieval

The SELECT statement was used to retrieve and verify data from the created tables.

SELECT * FROM accounts;

SELECT * FROM Transaction;

SELECT * FROM AccountBranches;

SELECT * FROM Loans;

SELECT * FROM Customer;
🛠️ Technologies Used
MySQL
MySQL Workbench
SQL
📚 SQL Concepts Practiced

This project covers the following SQL concepts:

USE
CREATE TABLE
SELECT
ALTER TABLE
ADD COLUMN
MODIFY COLUMN
SQL Data Types
Data Types Used
INT
VARCHAR
FLOAT
DATE
🎯 Learning Objectives

Through this SQL lab, I practiced:

Creating and selecting a database
Creating tables using SQL
Defining columns and data types
Retrieving table data using SELECT
Adding new columns using ALTER TABLE
Modifying existing column definitions
Working with a banking-related database structure

📌 Project Outcome

The project successfully creates a basic banking database structure with tables for accounts, transactions, account branches, loans, and customers.

The Customer table was further modified by adding a DateOfBirth column and changing the Phone column size from VARCHAR(15) to VARCHAR(20).

👩‍💻 Author

Nikita Sabale

Computer Engineering Graduate
