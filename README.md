# Sql-Product-Sales-Analysis
This project performs an in-depth SQL-based analysis of a product sales dataset using the Chinook relational database (available on Kaggle). The goal was to analyze transactional sales data stored across multiple related tables and extract meaningful business insights using structured SQL queries.

By applying JOINs, aggregations, window functions, and business logic, the project demonstrates how raw relational data can be transformed into actionable insights for decision-making.

🎯 Objectives

- Analyze product sales performance using SQL
- Identify top-selling tracks and products
- Calculate revenue per country and region
- Evaluate monthly sales performance trends
- Rank products using window functions

Demonstrate practical use of:
- JOIN operations
- Aggregations (SUM, COUNT, AVG)
- GROUP BY and HAVING clauses
- Window functions (RANK, ROW_NUMBER)

📂 Dataset

Dataset Used: Chinook Database (Kaggle)

The Chinook database simulates a digital music store and contains multiple related tables such as: Customers, Invoices, Invoice Items, Tracks, Albums, Artists, Genres, Employees etc.

🛠 Tools and Libraries 

- Numpy, Matplotlib, Pandas
- SQL (SQLite / PostgreSQL / MySQL / BigQuery)
- Python (for executing SQL queries)
- Relational Database Concepts
- Window functions (RANK, ROW_NUMBER)
- Aggregations & Grouping

🔍 Methodology
1. Data Exploration
- load and review database schema
- Identify primary and foreign keys
- Understand table relationships

2. JOIN Operations: Combine tables such as:
- Invoice + Invoice_Items
- Tracks + Albums + Artists
- Customers + Invoices

3. Aggregation & Business Metrics : Key metrics calculated:
- Total revenue per product
- Revenue per country
- Monthly sales performance
- Number of purchases per customer

4. Window Functions & Ranking : Applied advanced SQL features:
- ROW_NUMBER()
- RANK()

📈 Key Outputs and business insights 

- Top-selling tracks globally
- Revenue distribution by country
- Monthly revenue trends
- Compare performance within regions
- Ranked product lists using window functions
- Top sales track per country

These insights can help businesses in the follwing ways:
- Optimize inventory decisions
- Target high-value markets
- Focus marketing on top-performing products
- Improve strategic pricing decisions

⭐ Future Improvements

- Build interactive dashboards (Power BI / Tableau)
- Automate reporting with Python
- Extend analysis with customer segmentation
- Implement advanced analytics using SQL + Machine Learning
- Optimize query performance for large-scale databases
