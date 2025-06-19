# 🧾 Portfolio Management System

A full-stack, relational database-backed simulation of a modern-day stock portfolio management system. It demonstrates schema design, transactional workflows, stored procedures, views, triggers, and user-defined functions for financial portfolio management.

---

## 🚀 Project Overview

The **Portfolio Management System** enables users to:
- Track personal stock holdings and account balances
- Execute trades (Buy/Sell) across various order types
- Analyze trading behavior and market trends
- Monitor real-time and historical stock performance
- Ensure data accuracy and auditability with triggers and logs

---

## 🗂️ Core Features

- **Users & Accounts Management**  
  Maintains user profiles and their linked brokerage/retirement/personal accounts.

- **Transaction Engine**  
  Logs every buy/sell activity with calculated value and price snapshots.

- **Portfolio Holdings**  
  Tracks shares owned, quantity, and average buy prices for every user.

- **Market & Order Handling**  
  Simulates current stock prices and supports order types (Market, Limit).

- **Statements Generation**  
  Periodically summarizes total portfolio value per user.

- **Analytics Views**  
  Includes:
  - `UserPortfolioSummary`  
  - `RecentTransactions`  
  - `DailyTradingSummary`

- **Triggers & Audits**  
  Tracks stock sector changes with an `SECTOR_AUDIT` log using INSERT/UPDATE/DELETE triggers.

- **Stored Procedure**  
  `BuyStock`: Handles buy operations with checks for sufficient holdings and error handling.

- **UDF**  
  `GetTotalPortfolioValue`: Computes a user's complete current portfolio value.

---

## 🛠️ Tech Stack

- SQL Server 2017
- T-SQL (Transact-SQL)
- Microsoft Management Studio (SSMS)
- Platform: macOS

---

## 📁 Project Structure

```
portfolio-management-system/
├── GROUP7_CODE_FILE_SUBMISSION.txt        # Complete SQL code for schema, views, triggers, SP, UDF
├── GROUP-7-FINAL-PROJECT-IFT530.pdf       # Full report with design, screenshots, and test cases
├── GROUP-7-FINAL-PROJECT-SUMMARY.docx     # Executive summary of the project
├── README.md                              # Project documentation
```

---

## 👨‍💻 Authors

- Rahul Muddhapuram  
- Ishan Ojha

---

## 📌 Repository Name Suggestion

`portfolio-management-system-db`  
✅ Descriptive  
✅ Concise  
✅ SEO-friendly

Other options:
- `stock-portfolio-sql`
- `investment-db-simulator`
- `sql-portfolio-manager`

---

## 📄 License

Use, share, and modify as needed. Please credit the original authors.

---

## 📬 Contact

For queries or demo requests, feel free to reach out via LinkedIn or email.
