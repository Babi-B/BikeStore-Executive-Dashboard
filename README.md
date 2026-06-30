# BikeStore Executive Sales Dashboard (SQL, Excel & Tableau)

![SQL](https://img.shields.io/badge/SQL-Server-red)
![Excel](https://img.shields.io/badge/Excel-Analysis-green)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)

<figure>
  <img width="544" height="431" alt="image" src="https://github.com/user-attachments/assets/0b134d95-05e7-4dea-9981-4fb52ac6328b" /><br>
  <figcaption><em>Initial dashboard visualized on Excel</em></figcaption>
</figure>

 ## Project Overview
This project analyzes sales performance for a bicycle retail company operating across multiple stores in the United States. The goal was to develop an executive dashboard that provides management with a clear view of sales performance, customer behavior, product trends, and employee performance between 2016 and 2018.

The solution combines SQL for data extraction and transformation with Excel and Tableau for data analysis and visualization.

 ### Business Problem
 Management requires a centralized view of company sales performance across different stores, states, product categories, and brands.

The dashboard was designed to help stakeholders:

- Monitor revenue performance over time
- Identify top-performing stores and regions
- Evaluate sales representative performance
- Understand customer purchasing behavior
- Track product category and brand contributions to revenue

## Analysis Objective
The dashboard answers the following business questions:

- What are the total revenues by:
  - Region
  - Store
  - Product Category
  - Brand
- Who are the top customers by revenue generated?
- Which sales representatives generate the highest sales?
- How do sales trends vary across months and years?
- What products and categories contribute most to overall revenue?

## Tools & Technology used
| Tool                                | Purpose                            |
| ----------------------------------- | ---------------------------------- |
| SQL Server Management Studio (SSMS) | Data extraction and transformation |
| Microsoft Excel Power Query         | Data loading and preparation       |
| Microsoft Excel Pivot Tables        | Exploratory analysis               |
| Microsoft Excel Pivot Charts        | Initial visualization              |
| Tableau                             | Interactive dashboard development  |

## Data Preparation
The [BikeStores database](https://github.com/Babi-B/BikeStore-Executive-Dashboard/tree/main/SQL/SQL-Server-Sample-Database) consists of multiple related tables. A [consolidated analytical dataset](https://github.com/Babi-B/BikeStore-Executive-Dashboard/blob/main/SQL/Bikestore%20Joins%20file.sql) was created by joining sales, customer, product, store, brand, and staff information.

The [resulting dataset](https://github.com/Babi-B/BikeStore-Executive-Dashboard/blob/main/Dataset/Bikestore%20analysis%20dashboard.xlsx) was validated in SQL Server before being imported into Excel Power Query and Tableau for further analysis and dashboard development.

## Dashboard Features
- Revenue KPI tracking
- Sales trend analysis by year and month
- Store performance comparison
- Regional sales breakdown
- Top customers ranking
- Top sales representative ranking
- Product category analysis
- Brand performance analysis
- Interactive filtering and drill-down capabilities

## Dashboard Preview

https://github.com/user-attachments/assets/9ba981f5-539d-4149-81a0-f024affe2a59

## Key Insights

- Baldwin Bikes generated the highest overall revenue, making it the company's strongest-performing store.
- Mountain Bikes accounted for 35.33% of total sales revenue, indicating strong customer demand within this category.
- Sales exhibited seasonal fluctuations, with revenue peaking during the spring months.
- New York contributed the largest share of company revenue, outperforming all other states.
- Revenue generation was concentrated among a relatively small group of high-value customers.

# Project Structure
```text
BikeStore-Executive-Dashboard/
│
├── SQL/
│   └── data_extraction.sql
│
├── Dataset/
│   └── bikestore_sales.csv
│
├── Dashboard/
│   └── BikeStore_Dashboard.twbx
│
├── Images/
│   └── dashboard_preview.png
│
└── README.md
```

## Challenges & Solutions

| Challenge | Solution |
|------------|------------|
| Data spread across multiple tables | Created a consolidated dataset using SQL joins |
| Repeated analysis requirements | Built reusable Pivot Tables and Pivot Charts |
| Need for executive-level reporting | Designed an interactive Tableau dashboard with filters and KPIs |
