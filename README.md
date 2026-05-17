# E-Commerce Database System

A complete **Single Vendor E-Commerce Database System** project built using **MySQL/PostgreSQL**.
This project demonstrates database design, normalization, relationships, constraints, queries, aggregation, views, and triggers.

---

## 📌 Project Overview

This project includes:

* ER Diagram Design
* Database Schema (DDL)
* Sample Data Insertion (DML)
* Complex SQL Queries
* Aggregation Functions
* JOIN Operations
* Subqueries
* Views & Triggers

---

# 🧩 Database Entities

The system contains the following entities:

* Users
* Products
* Categories
* Orders
* Order_Items
* Payments

---

# 🔗 Relationships

* One User → Many Orders
* One Order → Many Order Items
* One Product → One Category
* One Order → One Payment

---

# 🏗️ ER Diagram

## Main Relationships

| Entity   | Relationship          |
| -------- | --------------------- |
| Users    | Creates Orders        |
| Orders   | Contains Order_Items  |
| Products | Belongs to Categories |
| Payments | Linked with Orders    |

---

# 🗄️ Database Schema Features

The schema includes:

* PRIMARY KEY
* FOREIGN KEY
* UNIQUE
* NOT NULL
* DEFAULT
* CHECK Constraints

---

# 📥 Sample Data Included

| Table      | Records |
| ---------- | ------- |
| Users      | 10      |
| Products   | 15      |
| Categories | 5       |
| Orders     | 20      |
| Payments   | 20      |

---

# 🔍 SQL Queries Implemented

## Basic Queries

* SELECT
* WHERE
* LIKE
* IN / NOT IN
* ORDER BY
* LIMIT

### Example Tasks

* Find users whose name starts with 'A'
* Get products under a specific category
* Find orders within a date range
* Display available products only

---

# 📊 Aggregation Queries

Implemented using:

* COUNT()
* SUM()
* AVG()
* GROUP BY
* HAVING

### Example Tasks

* Total sales per user
* Total orders per day
* Average product price by category
* Users who spent more than 5000

---

# 🔗 JOIN Queries

The project demonstrates:

* INNER JOIN
* LEFT JOIN
* Multiple Table JOIN

### Example

* Show order details with user and product information

---

# 📦 Bonus Features

## ✅ View

Created an `order_summary` view for simplified reporting.

## ✅ Trigger

Implemented trigger to:

* Automatically reduce product stock after placing an order

---

# 📁 Project Structure

```bash
E-Commerce_Database_System/
│
├── 1. ER Diagram/
│   └── E-Commerce Database System.jpg
│
├── 2. E-Commerce Database System.sql
│   
│
├── 3. Query outputs (screenshots)/
│   └── query_outputs/
│
└── README.md
```

---

# ⚙️ Technologies Used

* MySQL / PostgreSQL
* SQL
* drawsql.app (ER Diagram)

---

# 🚀 How to Run

## 1️⃣ Create Database

```sql
CREATE DATABASE ecommerce_db;
```

---

## 2️⃣ Import SQL Files

Run files in this order:

```bash
2. E-Commerce Database System.sql
```

---

# 📄 Final Submission Includes

* ✅ ER Diagram (PDF/Image)
* ✅ SQL Files (DDL + DML + Queries)
* ✅ Query Output Screenshots

---

# 📚 Learning Outcomes

After completing this project, you will understand:

* Database normalization
* Relational database design
* SQL constraints
* JOIN operations
* Aggregation queries
* Views and triggers
* Real-world database implementation

---

# 👨‍💻 Author

**MD YEAMIN HOSSAIN FUHAD**
