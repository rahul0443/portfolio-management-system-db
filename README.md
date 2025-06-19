# 📈 Portfolio Management System

A full-featured stock portfolio management system built with a relational database architecture. This project demonstrates the design and implementation of a trading platform database — capable of handling users, accounts, trades, market pricing, and portfolio reporting — using SQL and core data management principles.

---

## 🚀 Overview

This system enables users to:
- Track personal stock holdings and account balances
- Place and manage buy/sell orders (Market & Limit)
- Log and audit all transactions
- Analyze real-time and historical stock price trends
- Generate portfolio value summaries over time

---

## 💡 Key Features

- **User & Account Management**  
  Support for multiple account types (Personal, Brokerage, Retirement)

- **Order Processing System**  
  Handles Market and Limit orders with status tracking (Pending, Executed, Canceled)

- **Transaction Engine**  
  Stores detailed trade history with timestamps and pricing

- **Portfolio Tracker**  
  Tracks live share quantities and average purchase prices

- **Market Data Logs**  
  Simulates dynamic pricing and price history for stocks

- **Analytics Views & Reports**  
  Includes user-level summaries, order books, and performance snapshots

- **Triggers & Audits**  
  Logs sensitive updates (e.g., sector changes) for auditability

- **Stored Procedure**  
  `BuyStock` procedure validates transactions and adjusts holdings

- **User-Defined Function (UDF)**  
  Calculates total portfolio value from current holdings

---

## ⚙️ Technologies Used

- SQL Server 2017
- T-SQL (Transact-SQL)
- Microsoft SQL Server Management Studio (SSMS)

---

## 📂 Repository Contents

```
portfolio-management-system-db/
├── code.txt       # Complete SQL script (tables, procedures, views, triggers)
├── Report.pdf     # Detailed report with architecture, logic, and test cases
├── README.md      # Project overview and documentation
├── .gitignore     # Ignored system/editor-specific files
```

---

## 👥 Authors

- Rahul Muddhapuram  
- Ishan Ojha

---

## 📄 License

This project is shared for reference and educational purposes only. Redistribution or commercial use is not permitted without explicit permission from the authors.

---

## 📬 Contact

For professional inquiries or demonstrations, please reach out via LinkedIn or email.
