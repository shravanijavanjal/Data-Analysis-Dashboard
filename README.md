# Market Dynamics & Performance Insights Dashboard

## Project Objective
To transform raw commercial data from **Market Dataset.xlsx** into an interactive, actionable business intelligence solution within **market-dataset-powerbi.pbix**. The goal is to track sales trends, evaluate market share, analyze customer/regional segments, and empower stakeholders with data-driven decision-making capabilities.

---

## 📊 Dataset & Dashboard Quick Links
* **Data Source:** [Download Market Dataset](https://github.com/shravanijavanjal/Data-Analysis-Dashboard/blob/main/Market%20Dataset.xlsx)
* **Live View:** [View Dashboard Screenshot](https://github.com/shravanijavanjal/Data-Analysis-Dashboard/blob/main/Screenshot%20202026-06-28%2020235521.png)

---

## Key Performance Indicators (KPIs)
* **Total Revenue / Sales:** Tracks the absolute monetary value generated from the market to monitor growth.
* **Profit Margin (%):** Evaluates financial health by calculating net profit divided by revenue across different categories.
* **Sales Growth Rate (YoY / MoM):** Measures the percentage change in sales compared to previous periods to spot seasonal trends.
* **Average Order Value (AOV) / Unit Volume:** Analyzes the average spend per transaction and the total unit volume sold.
* **Customer Acquisition / Market Share:** Monitors the proportional performance of business segments against the broader market.

---

## Project Process

### 1. Data Ingestion & ETL (Extract, Transform, Load)
* Imported the raw data from **Market Dataset.xlsx** into Power BI's Power Query Editor.
* Cleaned and transformed the dataset by handling missing values, optimizing data types, removing duplicates, and standardizing categorical columns.

### 2. Data Modeling
* Designed an optimized **Star Schema** data model by separating business facts (sales/transactions) from specific dimensions (dates, geography, and product details).
* Established active relationships between tables to ensure precise cross-filtering and high dashboard performance.

### 3. DAX Calculations
* Authored custom **DAX (Data Analysis Expressions)** measures and calculated columns for advanced metrics, including Year-to-Date (YTD) sales, dynamic profit margins, and period-over-period growth comparisons.

### 4. Data Visualization & Dashboard Design
* Developed an intuitive, interactive layout inside **market-dataset-powerbi.pbix**.
* Utilized dynamic charts (bar charts, line graphs, matrix tables, and map visuals) paired with interactive slicers to allow stakeholders to seamlessly drill down by time, region, and product category.

---

## 🛠️ Tech Stack Used
* **BI Platform:** Microsoft Power BI Desktop
* **Data Transformation:** Power Query
* **Modeling & Analytics:** DAX (Data Analysis Expressions)
* **Data Source:** Microsoft Excel (`.xlsx`)
