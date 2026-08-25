# 🏦 Banking Loan Risk & Customer Analytics

## 📊 Power BI Portfolio Project

An interactive **Banking Loan Risk & Customer Analytics Dashboard** developed in Microsoft Power BI to analyze loan portfolio performance, customer behavior, credit risk, NPA exposure, collections, geographical trends, and employee performance.

The project uses a **Star Schema data model** with 100,000 loan transactions supported by customer, branch, employee, loan product, date, location, loan status, and payment method dimensions.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall loan portfolio performance
- Monitor loan applications and loan status
- Evaluate loan product performance
- Identify high-risk and default loans
- Analyze NPA and outstanding balances
- Monitor collection and repayment performance
- Analyze geographical loan distribution
- Evaluate employee performance
- Support data-driven banking decisions

---

## 📁 Dataset Overview

The project contains **9 related CSV datasets with 124,323 total records**.

| Dataset | Rows | Columns | Purpose |
|---|---:|---:|---|
| Fact_Loan | 100,000 | 29 | Main loan transaction and risk data |
| Dim_Customer | 20,000 | 20 | Customer demographics and financial profile |
| Dim_Branch | 250 | 11 | Branch information and targets |
| Dim_Employee | 1,000 | 11 | Employee details and performance |
| Dim_Loan_Product | 40 | 10 | Loan product information |
| Dim_Date | 2,922 | 11 | Date and financial calendar |
| Dim_Location | 100 | 10 | Geographic information |
| Dim_Loan_Status | 6 | 3 | Loan status classification |
| Dim_Payment_Method | 5 | 3 | Payment method information |
| **Total** | **124,323** | — | **9 related datasets** |

### ⭐ Main Fact Table

`Fact_Loan` contains **100,000 loan-level records** and acts as the central fact table.

The dimension tables provide descriptive information used for filtering, grouping, and analysis.

---

## 🏗️ Data Model

The project follows a **Star Schema** architecture.

```text
                         Dim_Date
                            │
                            │
Dim_Customer ───────────────┤
Dim_Branch ─────────────────┤
Dim_Employee ────────────────┤
Dim_Loan_Product ────────────┤
Dim_Location ────────────────┤
Dim_Loan_Status ──────────────┤
Dim_Payment_Method ───────────┤
                            ▼
                       Fact_Loan
                      100,000 Rows

## 🖥️ Dashboard Slide Overview

The Power BI report consists of 9 interactive dashboard slides covering the complete banking loan analytics lifecycle.

| Slide | Dashboard |
|---:|---|
| 1 | Executive Loan Overview |
| 2 | Customer Analytics |
| 3 | Loan Portfolio Analysis |
| 4 | Loan Status Overview |
| 5 | Loan Product Analysis |
| 6 | Risk & NPA Analysis |
| 7 | Collection & Repayment Analysis |
| 8 | Geographical Analysis |
| 9 | Employee Performance |
