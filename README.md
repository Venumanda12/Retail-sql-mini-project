# Retail-sql-mini-project
# Retail Sales Analysis – SQL Mini Project

## Overview
This mini project involves analyzing retail sales data using SQL. The goal is to extract meaningful business insights such as customer purchase behavior, product category trends, and sales performance.

## Contents
- *Dataset:* Retail transaction data (.csv or .xlsx)
- *SQL Queries PDF:* A PDF containing key SQL queries and outputs
- *SQL Scripts:* Optional .sql files used for querying

## Objectives
- Identify the number of unique customers per category
- Filter sales by specific time frames (e.g., November 2022)
- Calculate average sales, quantities, and other KPIs
- Use window functions for advanced analytics

## Tools Used
- *Database:* SQLite / MySQL / PostgreSQL (specify what you used)
- *Language:* SQL
- *Platform:* GitHub

## Sample SQL Queries
```sql
-- Find unique customers by category
SELECT category, COUNT(DISTINCT customer_id) AS unique_customers
FROM retail
GROUP BY category;
