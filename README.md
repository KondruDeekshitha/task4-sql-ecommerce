# task4-sql-ecommerce
# SQL Practice Project – Mini E-commerce Database

## 📌 Project Description
This project is a mini e-commerce database created in **SQLite** for practicing core SQL concepts:
- SELECT, WHERE, ORDER BY, GROUP BY
- JOINS (INNER, LEFT, RIGHT)
- Subqueries
- Aggregate functions (SUM, AVG)
- Creating views for analysis
- Optimizing queries with indexes

The database contains three tables: `customers`, `orders`, and `products`, with sample data to simulate basic e-commerce operations.

---

## 📂 Files Included
- **mydatabase.db** – SQLite database file containing the tables and data.
- **queries.sql** – All SQL commands used for this task.
- **/screenshots** – Output screenshots of query results.
- **README.md** – This document.
- *(Optional)* CSV files for dataset import if needed.

---

## 🛠 How to Open and Use the Database
1. **Install DB Browser for SQLite**  
   Download from: [https://sqlitebrowser.org/dl/](https://sqlitebrowser.org/dl/)

2. **Open the database**  
   - Launch DB Browser for SQLite.
   - Click **Open Database** and select `mydatabase.db`.

3. **Run queries**  
   - Go to the **Execute SQL** tab.
   - Copy and paste a query from `queries.sql`.
   - Click the **Play ▶️** button to see results.

---

## ▶️ Example Query
**Goal:** Show all customers from the state "SP"
```sql
SELECT * FROM customers
WHERE state = 'SP';
