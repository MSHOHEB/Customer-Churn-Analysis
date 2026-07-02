# 📊 Customer Churn Analysis — Capstone SQL Project

![MySQL](https://img.shields.io/badge/MySQL-8.0+-blue?logo=mysql)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Rows](https://img.shields.io/badge/Total_Rows-9300+-orange)
![Queries](https://img.shields.io/badge/SQL_Queries-25-purple)
![Churn](https://img.shields.io/badge/Churn_Rate-24%25-red)

A complete **Customer Churn Analysis Capstone Project** for **TeleConnect India Pvt. Ltd.**
9300+ rows across 5 tables with 25 business-focused SQL queries.

---

## 🎯 Business Problem

> TeleConnect India is losing **24% of its customers** every year.
> This project identifies **why customers churn**, **which segments are at risk**,
> and provides **data-driven recommendations** to reduce churn.

---

## 🗃️ Database Structure

| Table | Rows | Description |
|-------|------|-------------|
| 👥 customers | 1,000 | Demographics, plan, contract, churn status |
| 🌐 services | 1,000 | Internet, streaming, security add-ons |
| 💰 billing | 6,000 | 6 months billing history per customer |
| 🎫 support_tickets | 1,063 | Customer complaints and support history |
| ❌ churn_records | 253 | Churned customers with reasons & satisfaction |
| **TOTAL** | **9,316** | |

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `customer_churn_analysis.sql` | Complete SQL (CREATE + INSERT + 25 Queries) |
| `customers.csv` | Customer dataset (1000 rows) |
| `services.csv` | Services dataset (1000 rows) |
| `billing.csv` | Billing dataset (6000 rows) |
| `support_tickets.csv` | Support tickets dataset (1063 rows) |
| `churn_records.csv` | Churn records dataset (253 rows) |
| `README.md` | Project documentation |

---

## 🚀 How to Run

### ✅ Option 1 — MySQL (Recommended)

    -- Step 1: Open MySQL Workbench
    -- Step 2: File → Open SQL Script
    -- Step 3: Select customer_churn_analysis.sql
    -- Step 4: Click Run ▶️

### Option 2 — DB Browser for SQLite
1. Download from https://sqlitebrowser.org/
2. New Database → Execute SQL → paste file content

### Option 3 — Online SQL Editor
Paste queries at https://sqliteonline.com/

---

## 📊 25 Business SQL Queries

| # | Business Question | Concepts Used |
|---|-------------------|---------------|
| 1 | Overall Churn Rate | COUNT, SUM, ROUND |
| 2 | Churn by Contract Type | GROUP BY, ORDER BY |
| 3 | Churn by Plan | GROUP BY, CASE |
| 4 | Churn by Tenure Group | CASE WHEN, GROUP BY |
| 5 | Top Churn Reasons | GROUP BY, AVG |
| 6 | City-wise Churn | GROUP BY, LIMIT |
| 7 | Revenue Lost to Churn | SUM, CASE WHEN |
| 8 | Senior Citizen Analysis | CASE WHEN |
| 9 | Payment Method vs Churn | GROUP BY |
| 10 | Internet Service vs Churn | JOIN, GROUP BY |
| 11 | Support Tickets vs Churn | Subquery, LEFT JOIN |
| 12 | Late Payment vs Churn | JOIN, Subquery |
| 13 | Monthly Revenue Trend | GROUP BY, DATE |
| 14 | High Value Churned Customers | JOIN, WHERE |
| 15 | Churn by Gender | GROUP BY |
| 16 | Tech Support Impact | JOIN, CASE WHEN |
| 17 | Satisfaction by Churn Reason | AVG, MIN, MAX |
| 18 | State-wise Revenue & Churn | GROUP BY |
| 19 | Support Resolution Rate | AVG, ROUND |
| 20 | Partner & Dependents Effect | CASE WHEN |
| 21 | Streaming Service vs Churn | JOIN |
| 22 | Age Group Analysis | CASE WHEN |
| 23 | Unpaid Bills of Churned | HAVING, SUM |
| 24 | Customer Lifetime Value (CLV) | AVG, GROUP BY |
| 25 | Complete Churn Risk Profile | Multi-JOIN, Final Report |

---

## 🔍 Key Findings

| Finding | Insight |
|---------|---------|
| 📉 Overall Churn Rate | 24% |
| ⚠️ Highest Risk Group | Month-to-Month contract customers |
| 💸 Monthly Revenue Lost | ~24% of total revenue |
| 😠 #1 Churn Reason | Better Price Elsewhere |
| 📞 Support Impact | More tickets = Higher churn risk |
| 👴 Senior Citizens | Churn more than non-seniors |
| 💳 Safest Payment | Auto Debit = Lowest churn |

---

## 💡 Business Recommendations

1. **Lock customers in Annual Contracts** — Month-to-Month churn 3x more
2. **Launch Price Match Program** — #1 reason is better price elsewhere
3. **Improve Tech Support** — No support = higher churn
4. **Senior Citizen Retention Plan** — Special discounts for 60+
5. **Encourage Auto Debit** — These customers stay longest
6. **Resolve Tickets Faster** — High ticket count = High churn risk

---

## 📅 Daily Development Log

| Day | Update |
|-----|--------|
| Day 1 | ✅ Created repository and README |
| Day 2 | ✅ Uploaded customers.csv (1000 rows) |
| Day 3 | ✅ Uploaded services.csv (1000 rows) |
| Day 4 | ✅ Uploaded billing.csv (6000 rows) |
| Day 5 | ✅ Uploaded support_tickets.csv (1063 rows) |
| Day 6 | ✅ Uploaded churn_records.csv (253 rows) |
| Day 7 | ✅ Uploaded main SQL file with 25 queries |

---

## 🛠️ Tech Stack

- **MySQL 8.0+** — Primary database
- **MySQL Workbench** — GUI tool
- **CSV Files** — Raw dataset

---
