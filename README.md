# SQLite3 course (Python)

Welcome to `SQLite3 with Python` Course! This course is designed for beginners who want to learn practical database management using SQLite with Python. It's perfect for aspiring data scientists, software developers, or anyone looking to build small to medium-sized applications that require efficient data storage and manipulation without the complexity of a server-based database system.

The theoretical part of databases (e.g., relational databases, SQL fundamentals) has been covered in a prior MySQL course. Now, we aim to transition to SQLite3, emphasizing code execution and real-world usage scenarios.

# Learning Objectives

By the end of this course you will learn:

- Understand how **SQLite** differs from other database systems like **MySQL**.
- Set up and manage an SQLite database using Python’s sqlite3 module in Jupyter notebooks.
- Perform common database operations such as creating tables, inserting, updating, and deleting records.
- Write advanced SQL queries with JOIN, GROUP BY, HAVING, and aggregate functions.

# Course Format

1. Practical Execution: Every database operation is demonstrated through code in a Jupyter Notebook, allowing students to interactively execute queries, manipulate data, and see immediate results.
   
2. Step-by-Step Code Examples: Each lesson contains code snippets that demonstrate SQLite3 operations, making it easy for students to follow along and practice independently.
   
3. Hands-On Project: By the end of the course, students will apply their knowledge in a minor project (e.g., a School Management Database) to solidify their learning.

# How SQLite is Different from MySQL

| **SQLite**                                                | **MySQL**                                                         |
|-----------------------------------------------------------|--------------------------------------------------------------------|
| Serverless and lightweight, stores data in a single file. | Requires a separate server to run and manage databases.            |
| Best for small to medium-sized applications with fewer users. | Designed for large-scale applications with many concurrent users.   |
| No need for complex configuration or installation.         | Requires configuration and maintenance of a database server.       |
| Limited support for advanced features like user management and replication. | Provides extensive support for features like user permissions, replication, and clustering. |

# Course Outline

## Module 1: Introduction to SQLite3
- What is Database and it's types?
- What is SQLite?
- Comparison between SQLite and MySQL
- Key features and Use cases of SQLite
- Installation and configuration SQLite3 with setting Up SQLite3 locally.

Module 2: Creating and Managing Database
- Database creation
- Establishing connections using SQLite3
- `SQL CREATE TABLE` statements
- Inserting Data into Tables (using `execute()`, `executemany()`)
- How to reconnect with the database
- Using `DELETE` to remove records
- Using `DELETE` to delete database
- Writing `UPDATE` statements to update the database
- Closing the connection

## Module 3: Querying Data using clauses
- Writing basic `SELECT` statements
- **Condition-based** queries
  - `WHERE`
  - `AND`
  - `OR`
  - `IN`
  - `BETWEEN`
  - `LIKE`
- **Ordering** and **Pagination**
  - Using `ORDER BY` for sorting
  - Implementing pagination with `LIMIT` and `Offset` clause

## Module 4: Joins, Grouping and Aggregation
- Understanding different types of joins
- Combining data from multiple tables using Joins
- Grouping and Aggregating Data
  - Utilizing `GROUP BY` and `HAVING`
- Applying aggregate functions
  - `COUNT()`
  - `SUM()`
  - `AVG()`
  - `MIN()`
  - `MAX()`

# Project
At the end of the course, students will build a **School Management System** with a database consisting of tables for students, courses, enrollments, and grades. This project will involve creating tables, inserting data, writing queries, and performing transactions.

# Requirements
1. Python 3.x (Latest version)
2. Jupyter Notebook (else other Python IDE)
3. SQLite3 (usually included with Python)

# Prerequisites
1. This course assumes basic programming knowledge (variables, loops, functions) and a basic understanding of SQL, covered in previous MySQL lessons.
2. All examples are designed for practical, hands-on learning. Students are encouraged to practice in real-time by executing each query in Jupyter.

# Conclusion
By completing this course, you will gain valuable skills in using **SQLite3 with Python**, which are essential tools in modern data management and application development. You'll be equipped to handle your own database projects efficiently and collaborate with others in the programming community.

Let's embark on this exciting journey into the world of database management and practical SQL together!
