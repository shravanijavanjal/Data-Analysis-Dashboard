#  Market Dynamics & Performance Insights Dashboard

##  Project Objective
To transform raw commercial data from **Market Dataset.xlsx** into an interactive, actionable business intelligence solution within **market-dataset-powerbi.pbix**. The goal is to track sales trends, evaluate market share, analyze customer/regional segments, and empower stakeholders with data-driven decision-making capabilities.

---
##  Dataset Used
- Dataset Used: <a href="https://github.com/shravanijavanjal/Data-Analysis-Dashboard/blob/main/Market%20Dataset.xlsx">Dataset</a>
---

##  Key Performance Indicators (KPIs)
* **Total Revenue / Sales:** The absolute monetary value generated from the market.
* **Profit Margin (%):** Net profit divided by revenue to measure financial health across categories.
* **Sales Growth Rate (YoY / MoM):** Percentage change in sales compared to previous periods.
* **Average Order Value (AOV) / Unit Volume:** Total sales divided by the number of transactions/units sold.
* **Customer Acquisition / Market Share:** Proportional performance of segments against the total market.

---
- Dashboard Interaction: <a href="https://github.com/shravanijavanjal/Data-Analysis-Dashboard/blob/main/Screenshot%20202026-06-28%2020235521.png">View Dashboard</a>

##  Project Process

### 1. Data Ingestion & ETL (Extract, Transform, Load)
* Imported the raw data from **Market Dataset.xlsx** into Power BI's Power Query Editor.
* Cleaned the data by handling missing values, fixing data types, removing duplicates, and standardizing categorical columns.

### 2. Data Modeling
* Designed a star schema (or snowflake schema) by separating facts (sales/transactions) from dimensions (dates, geography, products).
* Established active relationships between tables to ensure precise filtering and optimal dashboard performance.

### 3. DAX Calculations
* Authored custom **DAX (Data Analysis Expressions)** measures and calculated columns for advanced metrics (e.g., Year-to-Date sales, profit margins, and period-over-period growth comparisons).

### 4. Data Visualization & Dashboard Design
* Developed an intuitive, interactive layout in **market-dataset-powerbi.pbix**.
* Utilized dynamic charts (bar charts, line graphs, matrix tables, and map visuals) paired with slicers to allow stakeholders to drill down by time, region, and product category.
