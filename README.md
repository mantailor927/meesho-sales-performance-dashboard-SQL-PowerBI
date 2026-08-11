# Meesho Sales & Performance Dashboard

I'm Mann, a student currently learning SQL, Power BI and data analysis.

I built this project as part of my learning and portfolio work using an e-commerce marketplace dataset. The main goal was to analyse sales, revenue, profit, customers, products, sellers and returns through an interactive Power BI dashboard.

## Dashboard

<img width="1439" height="812" alt="dashboard" src="https://github.com/user-attachments/assets/e3e267cf-7d53-4cd9-b085-d68c9d8b90fc" />


## Data Model

<img width="1920" height="1080" alt="Data modeling" src="https://github.com/user-attachments/assets/35e9ba58-245d-4e68-b07e-bbcd0c453988" />


## What I Analysed

The dashboard covers different areas of sales and business performance:

- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Return Rate
- Monthly Revenue Trend
- Revenue by State
- Revenue by Product
- Profit by Category
- Revenue by Gender
- Revenue by Payment Method
- Top Sellers
- Top Brands
- Top Customers

## Dashboard Filters

I added interactive filters to explore the data from different angles:

- Date
- Category
- Brand
- Product
- Rating

## SQL Analysis

I used MySQL to analyse the dataset and practise different types of SQL queries.

The project includes:

- SELECT and filtering
- WHERE
- GROUP BY
- HAVING
- Aggregate functions
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- UNION
- CASE WHEN
- Subqueries
- CTEs
- Window functions
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- LEAD()
- LAG()

Some of the analysis includes:

- Customer ranking
- Seller performance
- Top customers
- Top products
- Monthly sales analysis
- Profit analysis
- Customer order analysis
- Ranking within categories

## Power BI

I used Power BI to turn the analysed data into an interactive dashboard.

The Power BI work includes:

- Data modelling
- Table relationships
- Power Query
- Data cleaning
- DAX measures
- KPI cards
- Slicers
- Map visual
- Bar charts
- Line charts
- Donut charts
- Tables
- Interactive filtering

## DAX Functions Used

I practised and used different DAX functions while building the project:

- `SUM()`
- `COUNT()`
- `DIVIDE()`
- `YEAR()`
- `MONTH()`
- `FORMAT()`
- `IF()`
- `SWITCH()`
- `CALCULATE()`
- `FILTER()`

## DAX Measures

Some of the measures created for the dashboard include:

- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Total Returns
- Return Rate
- Profit Margin

For example, the Return Rate measure was calculated using the number of returned orders compared with total orders.

## Power Query

I also used Power Query while preparing the data for Power BI.

The work included:

- Data cleaning
- Changing data types
- Working with date columns
- Preparing columns for analysis
- Transforming the data before loading it into the model

## Tools Used

- MySQL
- Power BI
- DAX
- Power Query
- Excel

## Project Structure

```text
Meesho-Sales-Performance-Dashboard/
│
├── README.md
│
├── PowerBI/
│   └── Meesho_Project.pbix
│
├── SQL/
│   ├── 01_Basic_Queries.sql
│   ├── 02_Aggregation.sql
│   ├── 03_Joins.sql
│   ├── 04_Case_When.sql
│   ├── 05_CTE.sql
│   └── 06_Window_Functions.sql
│
├── Dataset/
│   ├── Customers.xlsx
│   ├── Orders.xlsx
│   ├── Products.xlsx
│   ├── Sellers.xlsx
│   └── Returns.xlsx
│
└── Screenshots/
    ├── dashboard.png
    └── data-model.png
