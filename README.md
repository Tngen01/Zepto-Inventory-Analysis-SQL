# Zepto-Inventory-Analysis-SQL

## Overview

This project analyzes Zepto product inventory data using PostgreSQL. The goal is to explore product categories, evaluate discounts, identify high-value products, analyze inventory levels, and generate business insights through SQL queries.

The project demonstrates practical SQL skills including data cleaning, data exploration, aggregation, filtering, sorting, conditional logic, and business analysis.

---

## Dataset

The dataset contains product-level information from Zepto, including:

* SKU ID
* Product Name
* Category
* MRP
* Discount Percentage
* Discounted Selling Price
* Available Quantity
* Product Weight
* Stock Status
* Inventory Quantity

---

## Tools Used

* PostgreSQL
* SQL
* pgAdmin (or PostgreSQL Server)

---

## Project Workflow

### 1. Database Creation

* Created a PostgreSQL table for storing product inventory data.
* Defined appropriate data types and constraints.

### 2. Data Exploration

Performed exploratory analysis such as:

* Total record count
* Sample data inspection
* Unique product categories
* Stock availability analysis
* Duplicate product identification
* Missing value checks

### 3. Data Cleaning

* Identified products with invalid prices.
* Removed records with MRP equal to zero.
* Converted prices from paise to rupees for accurate analysis.

### 4. Business Analysis

Executed SQL queries to answer key business questions:

* Top 10 products with the highest discounts
* High-MRP products currently out of stock
* Estimated revenue by category
* Premium products with low discounts
* Categories offering the highest average discounts
* Best-value products based on price per gram
* Product segmentation by weight category
* Total inventory weight by category

---

## SQL Concepts Demonstrated

* SELECT Statements
* Filtering with WHERE
* Sorting with ORDER BY
* Aggregate Functions
* GROUP BY
* HAVING Clause
* CASE Statements
* Data Cleaning
* Data Transformation
* Business KPI Analysis

---

## Key Insights

* Identified products offering the highest discounts.
* Analyzed categories generating the highest estimated revenue.
* Discovered high-value products that are currently out of stock.
* Compared discount trends across product categories.
* Evaluated product value using price-per-gram analysis.
* Assessed inventory distribution across categories.

---

## Results

The analysis provides actionable insights into:

* Inventory management
* Product pricing strategy
* Discount effectiveness
* Revenue optimization
* Stock availability monitoring

These insights can help improve product planning and operational decision-making.

---

## How to Run

1. Install PostgreSQL and pgAdmin.
2. Create a new database.
3. Import the dataset into PostgreSQL.
4. Open the SQL script file.
5. Execute the table creation script.
6. Load the dataset into the table.
7. Run the SQL queries to reproduce the analysis.

---

## Repository Structure

- README.md
- zepto_analysis.sql
- dataset.csv

---

## Author

**Rijingtngen Warlarpih**

Data Analytics Enthusiast with experience in SQL, Python, Power BI, and Business Intelligence. Passionate about transforming data into actionable insights and supporting data-driven decision-making.
