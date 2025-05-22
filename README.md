# 🏦 Bank Loan Report Dashboard (Excel)

This project presents an advanced **Excel-based dashboard** that visualizes and analyzes key metrics from a bank's loan dataset. It empowers data-driven decision-making by revealing trends, regional breakdowns, loan performance, and borrower profiles.

---

## 📘 Problem Statement

The objective is to build a robust reporting system that:
- Tracks **loan application trends**, funding, and repayment performance
- Evaluates **Good vs. Bad loans** to assess credit risk
- Offers interactive dashboards for insights by **term, purpose, region, income,** and **employment**
- Helps stakeholders monitor portfolio **health** and optimize **lending strategies**

---

## 📊 Key Performance Indicators (KPIs)

| KPI                           | Description                                                          |
|-------------------------------|----------------------------------------------------------------------|
| **Total Loan Applications**   | All submitted loan applications                                      |
| **Total Funded Amount**       | Sum of all disbursed loan amounts                                   |
| **Total Amount Received**     | Total repayments made by borrowers                                  |
| **Average Interest Rate**     | Average interest rate across all loans                              |
| **Average DTI**               | Average borrower debt-to-income ratio                               |
| **MTD/PMTD Metrics**          | Month-to-Date vs Previous MTD for trend analysis                    |
| **Good Loan %**               | % of loans with status: `Fully Paid` or `Current`                   |
| **Bad Loan %**                | % of loans with status: `Charged Off`                               |
| **Loan Status Grid**          | Grid view of metrics by loan status                                 |

---

## 🧠 Key Insights

- ✅ Most loans are 36-month terms in **Grade B and C**
- 🌎 Highest loan activity in **California, New York, and Texas**
- 📉 Lower **DTI** and verified employment improve approval likelihood
- 💰 Good loans dominate the portfolio, indicating strong credit discipline

---

## 🛠️ Tools Used

| Tool                      | Purpose                                                              |
|---------------------------|----------------------------------------------------------------------|
| **Microsoft Excel**       | Core dashboard development                                           |
| **Pivot Tables**          | Summarization of key metrics                                         |
| **Excel Charts**          | Bar, Line, Donut, Tree Map, Filled Map visualizations                |
| **Slicers**               | Interactive filtering by category                                    |
| **Excel Formulas**        | KPI logic using `SUM`, `IF`, `AVERAGE`, `COUNTIFS`, etc.             |
| **Conditional Formatting**| Color-based visual indicators                                        |
| **Power Query**           | Data transformation & cleaning                                       |

---

## 📈 Dashboards Overview

### 📌 Dashboard 1: Summary
- Total/MTD/PMTD Applications, Funding, Receipts
- Good vs Bad Loan metrics and ratios
- KPI cards and grid views for status-wise analysis

### 📍 Dashboard 2: Overview
- **Monthly Trends (Line Chart)**: Applications, Funded Amount, Amount Received
- **State-wise (Filled Map)**: Regional activity
- **Loan Term (Donut Chart)**: 36 vs 60 month distribution
- **Employment Length (Bar Chart)**: Risk vs experience
- **Purpose of Loan (Bar Chart)**: Reasons for borrowing
- **Home Ownership (Tree Map)**: Risk based on housing status

### 📋 Dashboard 3: Details
- Raw data display with slicers for ad-hoc review
- Filters for dynamic exploration by segment

---

## 📚 Domain Knowledge Summary

- Banks assess loans based on **credit reports, DTI, income, employment**, and **purpose**
- Loan statuses like `Fully Paid`, `Current`, and `Charged Off` drive portfolio classification
- Loan terms, employment stability, and verification status affect approval odds
- Data is analyzed to manage **risk**, ensure **compliance**, and improve **customer targeting**

---




