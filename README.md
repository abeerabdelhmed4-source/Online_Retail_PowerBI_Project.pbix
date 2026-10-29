# Online Retail Sales & Customer Analytics Dashboard

## 📌 Project Overview
This project presents an end-to-end Business Intelligence solution developed using **Power BI**, **Power Query**, and **Excel** for the comprehensive **Online Retail** dataset (500,000+ transactional records). The analysis models sales performance, customer purchasing behavior, returns rate, and geographical revenue distribution.

---

## 🛠️ Data Modeling & Architecture
- **Schema Type:** Star Schema.
- **Fact Table:** `Online Retail` (contains core sales and return transactions).
- **Dimension Tables:**
  - `Dim_Date`: Standard calendar table supporting time intelligence analysis.
  - `Dim_Customer`: Distinct customer profiles mapped to transactions.
  - `Dim_Product`: Unique product stock codes with normalized descriptions.
- **Relationships:** Built using unidirectional **1-to-Many (1:*)** relationships to ensure data integrity and filter accuracy.

---

## 📊 Key Business Metrics (DAX)
- **Total Sales:** $10.62M
- **Total Refunds:** $893.98K
- **Net Sales:** $9.73M
- **Total Orders:** ~24K unique transactions
- **Average Order Value (AOV):** $397.86

---

## 💡 Key Analytical Insights
1. **Regional Dominance:** The **United Kingdom** represents over **84%** of total revenue.
2. **Seasonality:** **November** experienced peak sales volume exceeding **$1.5M**, driven by seasonal holiday shopping.
3. **Hourly Purchasing Patterns:** Peak transaction activity concentrates around **10:00 AM – 12:00 PM**.

---

## 🎓 Academic Credit & Mentorship
Graduation Project submitted for the Data Analysis Diploma at **Smart Investment Solution (SIS)**.
Special thanks to mentors **Eng. Omar Mokhtar** and **Mr. Mustafa Nader** for their guidance and feedback throughout the program.
