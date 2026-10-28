# 🏦 Banking SQL Analysis

A **SQL-based banking data analysis project**  using synthetic banking data to simulate real-world banking scenarios.

The project demonstrates how SQL can be used to transform structured banking data into **meaningful business insights** through analytical queries, aggregations, joins, subqueries, and date-based analysis.

---

## 📌 Project Overview

This project analyzes a relational banking database to answer practical business questions related to:

* 👤 Customers
* 💳 Accounts
* 🏦 Branches
* 💰 Loans
* 💸 Transactions

The main objective is to understand relationships between different banking entities and use SQL to identify patterns in **customer behavior, account activity, loan exposure, and transaction trends**.

---

## 🗄️ Database Structure

The database contains interconnected entities representing a typical banking system:

| Table          | Description                          |
| -------------- | ------------------------------------ |
| `Customers`    | Stores customer information          |
| `Accounts`     | Contains customer account details    |
| `Branches`     | Stores branch-related information    |
| `Loans`        | Contains loan and borrowing details  |
| `Transactions` | Records account transaction activity |

These tables are connected through relational keys, allowing analysis across multiple banking entities.

---

## 🎯 Business Questions

The project answers practical questions such as:

* Which customers have multiple accounts?
* Which branches have the highest account activity?
* How does transaction volume change over time?
* Which customers have multiple loans?
* How are banking products distributed among customers?
* What patterns can be identified from customer transaction activity?

---

## 🔍 Key Analysis Areas

### 👤 Customer Analysis

Analyzes customer relationships with different banking products.

Examples:

* Identifying customers with multiple accounts
* Finding customers with multiple loans
* Comparing customer-level banking activity

### 💳 Account Analysis

Examines account distribution and activity.

Examples:

* Account distribution across branches
* Identifying inactive or low-activity accounts
* Comparing account activity between customers

### 💰 Loan Analysis

Analyzes customer borrowing and loan exposure.

Examples:

* Identifying customers with high loan amounts
* Finding customers with multiple loans
* Comparing loan exposure across customers

### 💸 Transaction Analysis

Studies transaction behavior and activity patterns.

Examples:

* Transaction volume over time
* Account-level transaction activity
* Identifying accounts with low transaction activity
* Comparing transaction patterns

---

## 🧠 SQL Concepts Used

This project demonstrates practical usage of:

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
* Date-based Analysis
* Multi-table Relationships
* Filtering and Aggregation
* Business-oriented SQL Queries

---

## 📊 Project Structure

```text
Banking/
│
├── 📁 Data Tables/
│
├── 📄 Bank_Analysis_1.sql
├── 📄 Loan_analysis.sql
├── 📄 Final_Report.sql
├── 📄 Bank_model.mwb
└── 📄 README.md
```

---

## 🛠️ Tools & Technologies

* **MySQL**
* **SQL**
* **MySQL Workbench**
* **Relational Database Concepts**
* **Git & GitHub**

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Saloni20404/bankingAnalysisUsingSQL
```

### 2. Open the Project

Open the project in **MySQL Workbench** or any MySQL-compatible SQL environment.

### 3. Load the Database

Import or execute the required files from the `Data Tables` folder to create and populate the banking tables.

### 4. Run the Analysis

Execute the SQL files to perform the analysis:

```text
Bank_Analysis_1.sql
Loan_analysis.sql
Final_Report.sql
```

### 5. Review the Results

Run the queries and analyze the generated results to understand customer, account, loan, branch, and transaction patterns.

---

## 📈 Learning Outcomes

Through this project, I strengthened my practical understanding of:

* Designing and working with relational databases
* Connecting multiple tables using joins
* Writing analytical SQL queries
* Using aggregate functions for business analysis
* Filtering grouped data using `HAVING`
* Working with subqueries
* Performing date-based analysis
* Translating real-world business questions into SQL queries

---


