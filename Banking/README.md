# 🏦 Banking Data Analysis using SQL

A practical **SQL data analysis project** focused on exploring banking data and solving real-world business questions using relational database concepts.

The project analyzes **customers, accounts, branches, loans, and transactions** to generate meaningful insights through SQL queries.

---

## 📌 Project Overview

This project demonstrates how SQL can be used to analyze banking operations and customer activity.

The analysis covers:

* 👤 Customer account analysis
* 🏦 Branch-wise account distribution
* 💰 Loan exposure analysis
* 👥 Customer loan activity
* 💸 Transaction analysis
* 📅 Monthly transaction trends
* 📊 Customer-level summary analysis

---

## 🗄️ Database Schema

The database consists of **five related tables**:

| Table          | Description                                    |
| -------------- | ---------------------------------------------- |
| `customers`    | Stores customer information                    |
| `accounts`     | Contains customer account details and balances |
| `branches`     | Contains bank branch information               |
| `loans`        | Stores customer loan information               |
| `transactions` | Contains debit and credit transaction records  |

The tables are connected using **primary keys and foreign keys**, allowing analysis across multiple entities.

---

## 🔍 Key Analysis

### 👤 Customer Analysis

* Identify customers with multiple accounts
* Analyze customer-level banking activity
* Summarize customer relationships with banking products

### 🏦 Branch Analysis

* Analyze account distribution across branches
* Compare banking activity between branches

### 💰 Loan Analysis

* Identify customers with higher loan exposure
* Analyze customers with multiple loans
* Compare loan amounts across customers

### 💸 Transaction Analysis

* Analyze debit and credit transactions
* Identify account activity levels
* Analyze monthly transaction trends
* Compare transaction volumes over time

---

## 🧠 SQL Concepts Used

The project demonstrates practical use of:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `INNER JOIN`
* `LEFT JOIN`
* Aggregate Functions

  * `COUNT()`
  * `SUM()`
  * `AVG()`
  * `MIN()`
  * `MAX()`
* Subqueries
* Date-based analysis
* Multi-table relationships

---

## 📁 Project Structure

```text
Banking/
│
├── 📄 Bank_Analysis_1.sql
├── 📄 Loan_analysis.sql
├── 📄 Final_Report.sql
└── 📄 README.md
```

---

## ▶️ How to Run

1. Open the SQL files in **MySQL Workbench** or another MySQL-compatible SQL environment.
2. Load the required banking tables and data.
3. Execute the SQL files individually or in the required order.
4. Review the query results to understand the generated business insights.

---

## 📈 Learning Outcomes

This project helped strengthen practical SQL skills including:

* Working with relational databases
* Joining multiple tables
* Performing grouped analysis
* Using aggregate functions
* Filtering aggregated results
* Writing subqueries
* Performing date-based analysis
* Converting business questions into SQL queries

---

## 🛠️ Tools & Technologies

* **MySQL**
* **SQL**
* **MySQL Workbench**
* **Relational Database Concepts**
* **Git & GitHub**

---
