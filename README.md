# 🏦 Bank Loan Report Dashboard (Excel)

This project features a fully interactive and visual **Excel-based dashboard** that analyzes a bank’s loan data. The dashboard helps track KPIs, monitor lending performance, and understand loan applicant behavior to support better decision-making.

---

## 📘 Problem Statement

The goal of this dashboard is to:

- Track loan application volume, funding, and repayment
- Monitor Month-to-Date (MTD) and Previous Month (PMTD) performance
- Evaluate **Good vs Bad loans** using loan status
- Visualize trends by region, term, employment, home ownership, and loan purpose
- Provide a consolidated report to assess the **health of the loan portfolio**

---

## 📊 Key Performance Indicators (KPIs)

| KPI                           | Description                                                          |
|-------------------------------|----------------------------------------------------------------------|
| **Total Loan Applications**   | All loan applications submitted                                      |
| **Total Funded Amount**       | Sum of loan principal amounts disbursed                             |
| **Total Amount Received**     | Total payments received from borrowers                              |
| **Average Interest Rate**     | Mean interest rate across all loans                                 |
| **Average DTI (Debt-to-Income)** | Average borrower DTI ratio                                        |
| **Good Loan %**               | Loans marked as ‘Fully Paid’ or ‘Current’                            |
| **Bad Loan %**                | Loans marked as ‘Charged Off’                                       |
| **MTD & PMTD Metrics**        | Month-to-date comparisons for trend analysis                        |
| **Loan Status Grid**          | Summary view by loan status                                         |

---

## 🧠 Key Insights

- 🔹 Most loans are 36-month terms in **Grades B & C**
- 🌍 Highest lending activity in **CA, NY, and TX**
- 💼 Employment verification and lower DTI ratios improve loan outcomes
- ✅ A majority of the portfolio consists of **Good Loans**
- 💳 Most common loan purpose is **debt consolidation**

---

## 📊 Dashboards Overview

### 📌 Dashboard 1: Summary
- Top-level KPIs: Applications, Funded Amount, Amount Received
- Loan performance breakdown: Good vs Bad
- KPI cards with MOM changes and loan status grid

### 📍 Dashboard 2: Overview
- **Line Chart**: Monthly trend of applications, funds, receipts
- **Filled Map**: Loan distribution by state
- **Donut Chart**: Loan term analysis (36 vs 60 months)
- **Bar Charts**:
  - Employment Length
  - Loan Purpose
- **Tree Map**: Home Ownership impact

### 📋 Dashboard 3: Details
- Full table with slicers
- Filter by loan status, purpose, term, state, etc.

---

## 🛠️ Tools Used

| Tool                      | Purpose                                                              |
|---------------------------|----------------------------------------------------------------------|
| **Microsoft Excel**       | Core dashboard building tool                                         |
| **Pivot Tables**          | KPI and metric aggregation                                           |
| **Charts**                | Line, Bar, Donut, Tree Map, Filled Map visualizations                |
| **Slicers**               | Interactive filtering experience                                     |
| **Excel Formulas**        | `SUM`, `COUNTIFS`, `AVERAGE`, `IF`, `TEXT`, etc.                     |
| **Conditional Formatting**| Highlights KPIs and deviations visually                              |
| **Power Query**           | Data transformation and preprocessing                                |

---

## 📁 Project Structure

Bank-Loan-Report-Dashboard/
│
├── dataset/
│ └── Bank_Loan_Report_ReadOnly.xlsx # Password-protected, editable only with access
│
├── images/
│ └── dashboard-screenshot.png # Visual preview of the dashboard
│
├── docs/
│ ├── Problem_Statement.md
│ ├── Terminologies.md
│ └── Domain_Knowledge.md

---



