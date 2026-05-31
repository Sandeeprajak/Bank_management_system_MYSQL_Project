# Bank_management_system_MYSQL_Project

# SQL Bank Management System

##  Project Overview

The Bank Management System is a SQL-based database project designed to simulate real-world banking operations. The project focuses on managing customers, bank accounts, transactions, employees, and banks through a structured relational database.

This project demonstrates database design, normalization, relationships, SQL querying, and analytical reporting using MySQL.

---

## Objectives

* Design a relational database for a banking system.
* Implement Primary Keys and Foreign Keys to maintain data integrity.
* Perform banking-related operations and analysis using SQL queries.
* Practice real-world SQL concepts used in Data Analyst and Database roles.

---

## Database Schema

### Tables Used

1. **Bank**

   * Bank ID
   * Bank Name
   * Full Address
   * National
   * Contact

2. **Customer**

   * Customer ID
   * Customer Name
   * Address
   * CKYC ID

3. **Bank Account**

   * Account Number
   * Account Type
   * Balance
   * Bank ID
   * Customer ID

4. **Transaction**

   * Transaction ID
   * Transaction Date & Time
   * Amount
   * Account Number

5. **Employee**

   * Employee ID
   * Employee Name
   * Contact Details
   * Employee Gender
   * Employee Address
   * Bank ID
   * Manager ID


# SQL Concepts Implemented

## Database Design

* Entity Relationship Diagram (ERD)
* Normalization
* Primary Keys
* Foreign Keys
* Constraints

## SQL Queries

* SELECT Statements
* Filtering (WHERE)
* Sorting (ORDER BY)
* Aggregations (COUNT, SUM, AVG, MAX, MIN)
* GROUP BY & HAVING

## Joins

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* SELF JOIN

## Advanced SQL

* CASE WHEN
* Subqueries
* Correlated Subqueries
* Common Table Expressions (CTEs)
* Window Functions

  * ROW_NUMBER()
  * RANK()
  * DENSE_RANK()
  * LAG()
  * LEAD()

## Database Objects

* Stored Procedures
* Triggers
* Indexes

---

## Business Analysis Performed

* Highest account balance in each bank
* Customers with multiple accounts
* Customers without transactions
* Duplicate data identification
* Bank-wise balance analysis
* Above-average account balance analysis
* Customer transaction analysis
* Ranking customers based on account balances

---

## Key Learnings

* Designed a complete relational banking database.
* Improved SQL query writing and optimization skills.
* Learned advanced SQL concepts including CTEs and Window Functions.
* Practiced solving real-world business problems using SQL.

---

## Tools Used

* MySQL Workbench
* SQL
* GitHub

---

## Author

**Sandeep Rajak**

Aspiring Data Analyst skilled in SQL, Excel, Power BI, and Python.
