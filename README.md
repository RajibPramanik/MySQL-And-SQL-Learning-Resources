# MySQL & SQL Learning Resources

A structured collection of notes, learning materials, PDFs, and resources for learning **SQL, MySQL, databases, and DBMS concepts**.

<img src="MySQLPic.png" alt="MySQL" width="800" height="450">

## 📚 Table of Contents

* [What are Data & Database?](#what-are-data--database)
* [Database Management System (DBMS)](#database-management-system-dbms)

  * [Types of DBMS](#types-of-dbms)
* [Structured Query Language (SQL)](#structured-query-language-sql)
* [How Does MySQL Work?](#how-does-mysql-work)
* [Why Use MySQL?](#why-use-mysql)
* [What is MySQL?](#what-is-mysql)

  * [Features of MySQL](#features-of-mysql)
* [When to Use MySQL](#when-to-use-mysql)
* [MySQL Data Types](#mysql-data-types)
* [Learning Resources](#learning-resources)

---

## What are Data & Database?

### Data

**Data** is a collection of facts, values, or information that can be stored and processed by a computer.

Examples:

* Name
* Age
* Email address
* Phone number
* Product price
* Student marks

### Database

A **database** is an organized collection of data that allows information to be stored, managed, retrieved, and updated efficiently.

For example, a student database may contain:

| ID | Name  | Age | Course                 |
| -: | ----- | --: | ---------------------- |
|  1 | Rajib |  21 | Computer Science       |
|  2 | Papu |  22 | Information Technology |

---

## Database Management System (DBMS)

A **Database Management System (DBMS)** is software that allows users and applications to create, store, organize, retrieve, update, and manage data in databases.

### Main Functions of a DBMS

* Create and manage databases
* Store and retrieve data
* Insert, update, and delete records
* Provide data security
* Manage user access
* Maintain data integrity
* Handle transactions
* Provide backup and recovery

### Types of DBMS

The major types of DBMS include:

1. **Hierarchical DBMS**
2. **Network DBMS**
3. **Relational DBMS (RDBMS)**
4. **Object-Oriented DBMS**
5. **NoSQL Database Systems**

MySQL is a **Relational Database Management System (RDBMS)**.

---

## Structured Query Language (SQL)

**SQL (Structured Query Language)** is a standard language used to communicate with relational databases.

SQL can be used to:

* Create databases and tables
* Insert data
* Retrieve data
* Update data
* Delete data
* Filter and sort records
* Join multiple tables
* Aggregate and analyze data
* Manage database permissions

### Common SQL Commands

```sql
SELECT * FROM students;

INSERT INTO students (name, age)
VALUES ('Rajib', 21);

UPDATE students
SET age = 22
WHERE name = 'Rajib';

DELETE FROM students
WHERE name = 'Rajib';
```

---

## How Does MySQL Work?

MySQL follows a **client-server architecture**.

The basic workflow is:

```text
Client / Application
        ↓
     MySQL Server
        ↓
     SQL Query
        ↓
 Query Processing
        ↓
     Database
        ↓
      Result
```

### Basic Process

1. A client or application sends an SQL query.
2. The MySQL server receives the query.
3. MySQL parses and processes the query.
4. The database engine reads or modifies the required data.
5. MySQL returns the result to the client.

MySQL can be used with applications written in languages such as **PHP, Python, Java, JavaScript, C++, and others**.

---

## Why Use MySQL?

MySQL is widely used because it is:

* Easy to learn
* Open source
* Fast and reliable
* Scalable
* Secure
* Cross-platform
* Widely supported
* Suitable for web applications
* Compatible with many programming languages

---

## What is MySQL?

**MySQL** is an open-source relational database management system (RDBMS) that uses SQL to store, manage, and retrieve structured data.

MySQL organizes data into **tables**, which contain rows and columns.

### Example

```text
Students
+----+--------+-----+------------------+
| ID | Name   | Age | Course           |
+----+--------+-----+------------------+
|  1 | Rajib  |  21  | Computer Science|
|  2 | Papu   |  22  | IT              |
+----+--------+-----+------------------+
```

---

## Features of MySQL

Some important features of MySQL include:

* **Open Source**
* **High Performance**
* **Reliability**
* **Scalability**
* **Security**
* **Cross-Platform Support**
* **Client-Server Architecture**
* **SQL Support**
* **Transaction Support**
* **Replication**
* **Backup and Recovery**
* **Large Community Support**

---

## When to Use MySQL

MySQL is a good choice when you need a relational database for applications such as:

* Web applications
* E-commerce websites
* Content management systems
* Business applications
* Inventory management systems
* Student management systems
* Banking and financial applications
* Reporting systems
* Data-driven applications

### Example Projects

MySQL can be used as the database for:

```text
Student Management System
Library Management System
E-Commerce Application
Hospital Management System
Inventory Management System
Blog / CMS
```

---

## MySQL Data Types

MySQL provides different data types for storing different kinds of values.

### Numeric Data Types

| Data Type | Description              |
| --------- | ------------------------ |
| `INT`     | Integer values           |
| `BIGINT`  | Large integer values     |
| `DECIMAL` | Exact decimal values     |
| `FLOAT`   | Floating-point numbers   |
| `DOUBLE`  | Double-precision numbers |

### String Data Types

| Data Type    | Description            |
| ------------ | ---------------------- |
| `CHAR`       | Fixed-length string    |
| `VARCHAR`    | Variable-length string |
| `TEXT`       | Long text              |
| `TINYTEXT`   | Small text             |
| `MEDIUMTEXT` | Medium-sized text      |
| `LONGTEXT`   | Very large text        |

### Date & Time Data Types

| Data Type   | Description   |
| ----------- | ------------- |
| `DATE`      | Date          |
| `TIME`      | Time          |
| `DATETIME`  | Date and time |
| `TIMESTAMP` | Timestamp     |
| `YEAR`      | Year          |

### Other Data Types

MySQL also supports data types such as:

* `BOOLEAN`
* `JSON`
* `BINARY`
* `VARBINARY`
* `ENUM`
* `SET`
* `BLOB`

---

## Learning Resources

This repository contains additional PDF resources for learning SQL and MySQL.

### 📖 SQL Book

**Book SQL.pdf**

A collection of SQL/MySQL learning material and notes.

[Book SQL.pdf](https://github.com/RajibPramanik/MySQL/blob/main/Book%20SQL.pdf?utm_source=chatgpt.com)

### 📘 SQL Learning Resources

Additional resources for learning SQL concepts and database queries.

[SQL Learning Resources.pdf](https://github.com/RajibPramanik/MySQL/blob/main/SQL%20Learining%20Resources.pdf?utm_source=chatgpt.com)

### 🔢 SQL Operators

Reference material covering SQL operators.

[SQL-Operators.pdf](https://github.com/RajibPramanik/MySQL/blob/main/SQL-Operators.pdf?utm_source=chatgpt.com)

---

## 📂 Repository Structure

```text
MySQL/
│
├── README.md
│
├── Book SQL.pdf
│
├── SQL Learining Resources.pdf
│
└── SQL-Operators.pdf
```

---

## 🎯 Learning Roadmap

A recommended order for learning the topics in this repository:

```text
Data
  ↓
Database
  ↓
DBMS
  ↓
RDBMS
  ↓
SQL Basics
  ↓
MySQL
  ↓
MySQL Data Types
  ↓
SQL Operators
  ↓
CRUD Operations
  ↓
Filtering & Sorting
  ↓
Aggregate Functions
  ↓
GROUP BY / HAVING
  ↓
Joins
  ↓
Subqueries
  ↓
Indexes
  ↓
Constraints
  ↓
Transactions
  ↓
Advanced MySQL
```

---

## 📚 Other Resources

A collection of useful resources for learning **SQL, MySQL, Database, and DBMS concepts**.


### 🔗 Official Documentation

* [MySQL Documentation](https://dev.mysql.com/doc/)
* [MySQL Reference Manual](https://dev.mysql.com/doc/refman/8.4/en/)
* [MySQL Downloads](https://dev.mysql.com/downloads/)
* [SQL Standard — ISO/IEC 9075](https://www.iso.org/standard/76583.html)

### 🌐 Online Learning Resources

* [W3Schools — SQL Tutorial](https://www.w3schools.com/sql/)
* [GeeksforGeeks — SQL](https://www.geeksforgeeks.org/sql/)
* [SQLBolt](https://sqlbolt.com/)
* [SQLZoo](https://sqlzoo.net/wiki/SQL_Tutorial)
* [HackerRank — SQL](https://www.hackerrank.com/domains/sql)

### 🧑‍💻 Practice

Practice SQL by working with:

* `SELECT` statements
* `WHERE` conditions
* `ORDER BY`
* `GROUP BY`
* Aggregate functions
* `JOIN`
* Subqueries
* Constraints
* Views
* Indexes
* Transactions
* Stored procedures


---

## 🤝 Contributing

Contributions, corrections, additional notes, and useful SQL learning resources are welcome.

If you find an error or have an improvement, feel free to open an **Issue** or submit a **Pull Request**.

---

## ⭐ Support

If this repository helps you learn **SQL or MySQL**, consider giving it a ⭐ on GitHub.

Happy Learning! 🚀
