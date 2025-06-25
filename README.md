# 🏦 Bank Management System (DBMS Project)

A comprehensive **Bank Management System** project designed and developed using **PostgreSQL** as part of the **Database Management Systems (DBMS)** curriculum.

> 🎓 Submitted by: **Sakshi Tripathi**  

---

## 🧩 Table of Contents

- [📘 Project Overview](#-project-overview)
- [🎯 Objectives](#-objectives)
- [🗂️ Database Schema](#-database-schema)
- [🛠️ Features](#-features)
- [🧪 SQL Highlights](#-sql-highlights)
- [📊 ER Diagram](#-er-diagram)
- [⚙️ Technologies Used](#️-technologies-used)
- [🎥 Demo](#-demo)
- [📌 Conclusion](#-conclusion)

---

## 📘 Project Overview

The **Bank Management System (BMS)** automates and streamlines core banking operations such as:

- Customer account management
- Loan processing
- ATM transactions
- Insurance management
- Online banking access
- Branch and employee operations

Using a **relational database model**, it ensures secure, real-time, and error-free operations, addressing the limitations of traditional manual banking systems.

---

## 🎯 Objectives

- Ensure **accuracy** in managing customer accounts, loans, and transactions.
- Design a **user-friendly** and **efficient** system for customers and staff.
- Implement **secure data handling** through robust database structures.
- Provide **real-time updates** and transactional reliability.
- Support **administrative tasks** like fraud detection and account management.

---

## 🗂️ Database Schema

The system includes 13+ normalized tables, including:

- `Customer_Info`
- `Account`, `Depositor`, `Borrower`
- `ATM_Transaction`, `Transaction_Info`
- `Cards`, `Online_Banking`
- `Loans`, `Loan_Payments`, `Insurance`
- `Branch`, `Employee`

Each table is connected through **primary and foreign key constraints** to maintain referential integrity and model real-world banking relationships.

---

## 🛠️ Features

### 👩‍💼 For Customers:
- Account creation and closure
- Balance inquiry and transaction history
- Money deposit, withdrawal, and transfers
- Secure login (password/OTP)
- Online banking and insurance services

### 🧑‍💼 For Administrators:
- Add/modify/delete customer accounts
- View and monitor transactions
- Set loan interest rates
- Suspend or reactivate accounts
- Generate reports for audits or fraud detection

---

## 🧪 SQL Highlights

💡 **52 SQL operations** have been implemented, including:

- **Table creation, insertion, deletion**
- **Aggregate functions**: `SUM`, `AVG`, `MAX`, `COUNT`
- **Advanced filtering** with `LIKE`, `BETWEEN`, `NOT`
- **Joins**: `INNER`, `LEFT`, `RIGHT`, `FULL OUTER`, `NATURAL`
- **Views**, **Aliases**, **Transactions**: `COMMIT`, `ROLLBACK`, `SAVEPOINT`
- **User permissions**: `GRANT`, `REVOKE`
- **Indexing**: Single and composite

---

## 📊 ER Diagram

The project includes a full **ER Diagram** showcasing:

- Entity relationships (Customer → Account, Loan, Insurance)
- Cardinality and keys
- Data dependencies and normalization
  
---

## ⚙️ Technologies Used

- **PostgreSQL** – for database design and execution
- **psql** – command-line interface for SQL interaction
- **DBMS Concepts** – keys, constraints, indexing, joins, transactions

---
## 📌 Conclusion

The **Bank Management System (BMS)** project demonstrates the practical application of database management concepts to a real-world scenario. By integrating PostgreSQL with structured relational design, it provides a secure, efficient, and user-friendly approach to banking operations.

This project helped achieve:
- Automation of key banking processes like account handling, loans, and transactions
- Real-time, accurate financial data management
- Enforcement of data integrity using keys, constraints, and normalization
- Enhanced understanding of SQL operations, including complex queries, joins, views, indexing, and transaction control

Overall, the project not only reinforced theoretical DBMS knowledge but also showcased how databases play a crucial role in building reliable and scalable enterprise-level applications.
