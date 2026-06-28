#  Market Dynamics & Performance Insights Dashboard

##  Project Objective
The goal of this project is to take raw sales data from **Market Dataset.xlsx** and turn it into an easy-to-use, interactive dashboard in **market-dataset-powerbi.pbix**. This dashboard helps business owners track sales, see how well different regions and products are doing, and make smarter business decisions based on real facts.

---

##  Dataset Used
- <a href="https://github.com/shravanijavanjal/Data-Analysis-Dashboard/blob/main/Market%20Dataset.xlsx">Dataset</a>
- <a href="https://github.com/shravanijavanjal/Data-Analysis-Dashboard/blob/main/Screenshot%202026-06-28%20235521.png">Dashboard</a>

---

##  Key Performance Indicators (KPIs)
* **Total Revenue:** The total amount of money made from sales to see how the business is growing.
* **Profit Margin:** Shows how healthy the business is financially by checking how much actual profit is made from sales across different items.
* **Sales Growth Rate:** Compares sales numbers over different months or years to find busy or slow seasons.
* **Average Order Value:** Shows the average amount of money a customer spends on a single order, along with the total number of items sold.
* **Customer Acquisition:** Tracks how well different parts of the business are performing compared to the whole market.

---

##  Project Process

### 1. Cleaning the Data (ETL)
* Brought the raw data from **Market Dataset.xlsx** into Power BI's Power Query Editor.
* Cleaned up the data by fixing empty spaces, correcting wrong data formats, removing repeating lines, and making sure all category names were neat and uniform.

### 2. Organizing the Data (Data Modeling)
* Organized the tables cleanly using a **Star Schema** (connecting a main sales table with simple lookup tables like dates, locations, and product details).
* Connected these tables together so that clicking on one chart automatically and smoothly updates all the other charts on the dashboard.

### 3. Creating Custom Calculations (DAX)
* Wrote custom formulas using **DAX** to calculate complex metrics, such as Year-to-Date (YTD) sales, profit percentages, and comparing this year's sales directly against last year's.

### 4. Designing the Dashboard (Data Visualization)
* Built a user-friendly, interactive dashboard page inside **market-dataset-powerbi.pbix**.
* Used clear charts (like bar charts, line graphs, tables, and maps) along with clickable filters so users can easily look closer at specific dates, regions, or products.

---

##  Tech Stack Used
* **Main Tool:** Microsoft Power BI Desktop
* **Data Cleaning:** Power Query
* **Formulas & Math:** DAX (Data Analysis Expressions)
* **Data Source:** Microsoft Excel (`.xlsx`)

---

##  Final Conclusion
This Power BI project takes messy spreadsheets and turns them into a clean, automated report. Instead of spending hours calculating numbers by hand from **Market Dataset.xlsx**, business leaders can now see their sales trends, profitable items, and top regions instantly in one place. This changes the way the business works—moving from simply looking at past results to actively planning for future growth.
