# Retail Data Analysis & SQL Integration
This project involves analyzing retail sales data using Python and SQL to uncover valuable insights, optimize sales strategies, and integrate the cleaned data into a SQL Server database for further reporting and analysis.

# Project Overview
Objective: Clean, transform, and analyze retail sales data to identify key insights such as top-selling products, sales trends, and growth metrics.
Technologies Used:
Python (Pandas) for data cleaning and analysis
SQL Server for storing and querying the cleaned data
SQLAlchemy for database interaction
Steps Involved
# Data Cleaning & Transformation:

Handle missing values by replacing 'Not Available' and 'unknown' with NaN.
Clean column names (e.g., making them lowercase and replacing spaces with underscores).
Derive new columns such as profit, sale price, and discount.
Date Handling:

Convert the order_date column to the proper datetime format for easier analysis.
Data Loading:

Load the cleaned and transformed data into SQL Server using SQLAlchemy to enable real-time querying and reporting.
SQL Queries:
Write SQL queries to:
engine = sal.create_engine('mssql://<username>:<password>@<server>/<database>?driver=ODBC+DRIVER+17+FOR+SQL+SERVER')
Running the Analysis
Download the orders.csv dataset and place it in the /data folder.
Run the Python script to clean, analyze, and load the data into SQL Server.

1. find top 10 highest reveue generating products
2. find top 5 highest selling products in each region
3. find month over month growth comparison for 2022 and 2023 sales eg : jan 2022 vs jan 2023
4. for each category which month had highest sales
5. which sub category had highest growth by profit in 2023 compare to 2022
