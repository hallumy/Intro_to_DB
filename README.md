# 📘 Introduction to Databases and SQL

This guide provides foundational concepts and practical skills needed to work effectively with databases, particularly using SQL. It is intended for beginners who are starting their journey into database management and SQL programming.

---

## 🌐 What is a Database?

A **database** is an organized collection of data that can be easily accessed, managed, and updated. It allows users and applications to store and retrieve data efficiently.

---

## 🗃️ Types of Databases

### 1. **SQL (Relational Databases)**
- Use structured tables with predefined schemas
- Data is accessed using **SQL**
- Examples: MySQL, PostgreSQL, SQLite, Oracle

### 2. **NoSQL (Non-relational Databases)**
- Flexible schema and data formats (JSON, key-value, graph, etc.)
- Scales horizontally
- Examples: MongoDB, Cassandra, Redis

---

## 🔤 What is SQL?

**SQL** stands for **Structured Query Language**. It is the standard language used to communicate with relational databases.

---

## 🐬 What is MySQL?

**MySQL** is a popular open-source relational database management system (RDBMS) that uses SQL. It is widely used in web applications and data-driven systems.

---

## 📚 Key Concepts

### ✅ What is a Relational Database?
A **relational database** organizes data into **tables (relations)** consisting of **rows and columns**, where each table has a unique key.

---

## 🔨 SQL Operation Categories

### 🔧 DDL – Data Definition Language
Used to define and modify database structure:
- `CREATE` – Create a database/table
- `ALTER` – Modify an existing table
- `DROP` – Delete tables or databases

### 📝 DML – Data Manipulation Language
Used to manipulate data within tables:
- `SELECT` – Retrieve data
- `INSERT` – Add new data
- `UPDATE` – Modify existing data
- `DELETE` – Remove data

---

## 🧪 CRUD Operations

The core operations for working with database records:
- **Create** – `INSERT INTO`
- **Read** – `SELECT`
- **Update** – `UPDATE`
- **Delete** – `DELETE`

---

## 🔍 Advanced SQL Techniques

- **Subqueries**: A query nested inside another query.
  ```sql
  SELECT name FROM Employees WHERE salary > (SELECT AVG(salary) FROM Employees);

