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
* [cite_start]**Total Revenue:** $55M [cite: 4]
* [cite_start]**Total Interest Earned:** $7.8M [cite: 7]
* [cite_start]**Total Transaction Volume:** 45M [cite: 5]
* [cite_start]**Total Transaction Count:** 656K [cite: 26]

## 🧠 Approach & Methodology

1.  **Data Extraction:** Imported data from CSV files into a SQL database to simulate a real-world data pipeline.
2.  **Data Processing:** Connected Power BI to the SQL database and performed data transformation in Power Query (checking for nulls, data type correction).
3.  **DAX Calculations:**
    * Created measures for *Current Week Revenue*, *Previous Week Revenue*, and *WoW (Week-on-Week) Growth*.
    * Used `SWITCH()` function to create dynamic groups for **Age** (e.g., 20-30, 30-40) and **Income** (High, Medium, Low).
4.  **Dashboard Design:** Designed two interactive pages:
    * **Transaction Report:** Focuses on revenue trends, card categories, and expenditure types.
    * **Customer Report:** Analyzes customer demographics, job roles, and regional performance.

## 💡 Key Insights

### 1. Revenue Analysis
* [cite_start]**Blue Card** category is the highest revenue contributor with **$46M**, followed by Silver ($6M), Gold ($2M), and Platinum ($1M) [cite: 31, 84-89].
* [cite_start]**Swipe** transactions dominate the usage method, accounting for **35M** compared to Chip (17M) and Online (3M) [cite: 90-97].
* [cite_start]**Q3** recorded the highest revenue at **$14.2M**, showing a strong mid-year performance[cite: 16].

### 2. Customer Segmentation
* [cite_start]**Job Role:** **Businessmen** contribute the most to revenue (**$17M**), followed by White-collar professionals ($10M) [cite: 40-45].
* [cite_start]**Education:** **Graduates** utilize credit cards the most, generating **$22M** in revenue [cite: 72-73].
* [cite_start]**Income Group:** High-income customers generate **$22M**, while Low-income groups surprisingly contribute significantly with **$10M**[cite: 151, 169].

### 3. Geographical Analysis
* [cite_start]**Top 5 States:** Texas (TX), New York (NY), and California (CA) are the leading states, contributing approximately **68%** of the total revenue [cite: 142-160].

## 📊 Dashboard Visuals

### Transaction Report
![Transaction Dashboard](path/to/your/screenshot1.png)
*Provides a high-level view of revenue metrics and weekly trends.*

### Customer Report
![Customer Dashboard](path/to/your/screenshot2.png)
*Deep dive into customer demographics, showing revenue by job, income, and education.*

### 📄 Full Report
> **[Download Full PDF Report](Credit%20Card%20report.pdf)**

## 🚀 Conclusion

The dashboard successfully provides a 360-degree view of credit card operations. The insights reveal that marketing strategies should focus on the **Blue Card** segment and the **Businessman/Graduate** demographics in **TX, NY, and CA** to maximize revenue. The high contribution of "Swipe" transactions suggests a need to promote "Online" and "Chip" usage for better security and digital adoption.
