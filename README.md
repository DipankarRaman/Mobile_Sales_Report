# Mobile_Sales_Report

# Interactive Sales Analysis Dashboard in Power BI
This project showcases an interactive dashboard built in Power BI, designed for analyzing sales data to identify trends, measure performance, and provide actionable insights.

# Mobile Sales Analysis Dashboard
## Table of Contents
- Project Overview
- ETL Process
- Key Features
- Technologies Used
- DAX Measures
- Dashboard Pages
- Guidance and Credits
- Screenshots
- Usage
 
## Project Overview
This project showcases an interactive Power BI dashboard designed to provide comprehensive insights into mobile sales data. The dashboard helps users identify trends, track sales performance, and derive actionable insights to support business decisions.

## ETL Process
**1. Data Import**: Imported raw sales data from an Excel file.

**2. Data Cleaning and Transformation**:
- Merged and split columns.
- Removed unnecessary rows and replaced specific values.
- Changed data types for consistency and analysis readiness.
 
**3. Data Modeling**:
- Established one-to-many and many-to-one relationships to ensure accurate data connections.

## Key Features

- **Visuals Created**:
   - &nbsp;Column, bar, line, area, funnel, and map charts.
   -  Table and pie charts for detailed breakdowns.
  
- **Filters and Interactions**:
   - &nbsp; Used drop-down slicers to filter data by mobile brand, model, payment method, and month.
   - &nbsp; Configured visual interactions using the Edit Interaction tool.
  
- **User Experience Enhancements**:
   - &nbsp; Added cards displaying key metrics: total sales, total quantity, transactions, and average price.
   - &nbsp; Incorporated a page navigator for seamless navigation between dashboard pages.
  
## Technologies Used

- **Power BI Desktop**

- **Power Query**

- **DAX (Data Analysis Expressions)**
 
## DAX Measures
Developed custom measures to enhance the analysis, including:

- **SUM()**: Aggregate total sales from the online store.

- **SUMX()**: Iterate and sum over a table to calculate sales performance.

- **COUNTROWS()**: Count the number of transactions in the sales data.

-**AVERAGE()**: Calculate the average order value.
-**TOTALMTD()**: Calculate the month-to-date total sales.
-**SAMEPERIODLASTYEAR()**: Compare current sales metrics with the same period in the previous year.
-**CALCULATE()**: Apply filters to modify the context of calculations for deeper insights.
- Created **a custom calendar table** for time-based analysis of sales trends.
Dashboard Pages
1. Dashboard
Filters: Mobile brand, mobile model, payment method, month.
Visuals:
Cards showing total sales, total quantity, transactions, and average price.
Map: Total sales by city.
Line chart: Total quantity by month.
Funnel chart: Customer ratings.
Pie chart: Transactions by payment method.
Bar chart: Top 3 total sales by mobile model.
Area chart: Total sales by day name.
Table chart: Brand, total sales, and transactions.
2. MTD Report
Filters: Same as the main dashboard.
Visuals:
Line chart: Month-to-date (MTD) sales analysis by year, quarter, month, and day.
Cards: Same metrics as the main dashboard.
3. Same Period Last Year
Filters: Same as the main dashboard.
Visuals:
Cards showing total sales, total quantity, transactions, and average price.
Table chart: Year, quarter, total sales, and same period last year.
Column charts: Sales by year, month, and quarter for comparison with the previous year.
Guidance and Credits
Special thanks to Satish Dhawale for guidance and mentorship throughout this project.

Screenshots
Here are some screenshots of the dashboard:

Dashboard Screenshot MTD Report Screenshot Same Period Last Year Screenshot

Usage
Open the .pbix file in Power BI Desktop.
Use the filters and slicers to explore the data.
Analyze key metrics and compare trends across different pages.
