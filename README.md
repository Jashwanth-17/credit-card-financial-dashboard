# 💳 Credit Card Financial Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=mysql&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analysis-005C84?style=for-the-badge&logo=googleanalytics&logoColor=white)

## 📄 Project Overview

This project involves the development of a comprehensive **Credit Card Weekly Dashboard** that provides real-time insights into key performance metrics and trends. The dashboard enables stakeholders to monitor credit card operations effectively, analyze customer behavior, and track revenue growth.

The goal was to bridge the gap between raw data and actionable insights, utilizing **SQL** for data extraction and **Power BI** for advanced visualization and DAX calculations.

## 🛠️ Tools & Technologies Used

* **Database:** MySQL (for data storage and retrieval)
* **ETL & Data Processing:** SQL, Power BI Power Query
* **Visualization:** Microsoft Power BI
* **Key Skills:** Data Modeling, DAX (Data Analysis Expressions), Data Cleaning, KPI Monitoring

## 📂 Dataset & Metrics

The analysis is based on a dataset containing over **10,000 transaction records**. Key tables used:
1.  **`credit_card.csv`**: Transaction-level details (Revenue, Interest, Transaction Count).
2.  **`customer.csv`**: Customer demographics (Age, Income, Job, Education).

**Key Performance Indicators (KPIs):**
* **Total Revenue:** $55M
* **Total Interest Earned:** $7.8M
* **Total Transaction Volume:** 45M
* **Total Transaction Count:** 656K

## 🧠 Approach & Methodology

1. **Data Extraction:** Imported data from CSV files into a SQL database to simulate a real-world data pipeline.
2. **Data Processing:** Connected Power BI to the SQL database and performed data transformation in Power Query (checking for nulls, data type correction).
3. **DAX Calculations:**
    * Created measures for *Current Week Revenue*, *Previous Week Revenue*, and *WoW (Week-on-Week) Growth*.
    * Used `SWITCH()` function to create dynamic groups for **Age** (e.g., 20-30, 30-40) and **Income** (High, Medium, Low).
4. **Dashboard Design:** Designed two interactive pages:
    * **Transaction Report:** Focuses on revenue trends, card categories, and expenditure types.
    * **Customer Report:** Analyzes customer demographics, job roles, and regional performance.

## 💡 Key Insights

### 1. Revenue Analysis
* **Blue Card** category is the highest revenue contributor with **$46M**, followed by Silver ($6M), Gold ($2M), and Platinum ($1M).
* **Swipe** transactions dominate the usage method, accounting for **35M** compared to Chip (17M) and Online (3M).
* **Q3** recorded the highest revenue at **$14.2M**, showing a strong mid-year performance.

### 2. Customer Segmentation
* **Job Role:** **Businessmen** contribute the most to revenue (**$17M**), followed by White-collar professionals ($10M).
* **Education:** **Graduates** utilize credit cards the most, generating **$22M** in revenue.
* **Income Group:** High-income customers generate **$22M**, while Low-income groups surprisingly contribute significantly with **$10M**.

### 3. Geographical Analysis
* **Top 5 States:** Texas (TX), New York (NY), and California (CA) are the leading states, contributing approximately **68%** of the total revenue.
## 📸 Screenshots

### Transaction Report
![Transaction Dashboard](screenshots/Transaction_report.png)
*Provides a high-level view of revenue metrics and weekly trends.*

### Customer Report
![Customer Dashboard](screenshots/Customer_report.png)
*Deep dive into customer demographics, showing revenue by job, income, and education.*

### 📂 File Structure
* [`Credit_Card_dashboard.pbix`](dashboard/Credit_Card_dashboard.pbix): The source Power BI file.
* [`Credit_Card_Report.pdf`](dashboard/Credit_Card_Report.pdf): A static PDF version of the report.


## 🚀 Conclusion

The dashboard successfully provides a 360-degree view of credit card operations. The insights reveal that marketing strategies should focus on the **Blue Card** segment and the **Businessman/Graduate** demographics in **TX, NY, and CA** to maximize revenue. The high contribution of "Swipe" transactions suggests a need to promote "Online" and "Chip" usage for better security and digital adoption.
