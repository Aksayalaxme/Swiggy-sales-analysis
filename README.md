# Swiggy Data Analysis – SQL Project

## Project Overview

This project analyzes Swiggy food-order data using **SQL Server** to perform data cleaning, database modelling, KPI analysis, and business-focused analysis.

The project transforms raw Swiggy data into a structured **Star Schema** consisting of dimension tables and a fact table, followed by SQL queries to generate meaningful business insights.

## Tools & Technologies

* SQL Server
* SQL
* SSMS
* GitHub

## Dataset

The dataset contains Swiggy-related information such as:

* State
* City
* Location
* Order Date
* Restaurant Name
* Category
* Dish Name
* Price (INR)
* Rating
* Rating Count

## Project Workflow

### 1. Data Validation & Cleaning

Performed:

* Null value checks
* Blank/empty value checks
* Duplicate record identification
* Duplicate record removal

### 2. Database Modelling

Created a **Star Schema** with:

**Dimension Tables**

* `dim_date`
* `dim_location`
* `dim_restaurant`
* `dim_category`
* `dim_dish`

**Fact Table**

* `fact_Swiggy_Data_Analysis`

The fact table contains foreign keys connecting it to the dimension tables.

### 3. KPI Analysis

Calculated key metrics including:

* Total Orders
* Total Revenue
* Average Dish Price
* Average Rating

### 4. Business Analysis

The project analyzes:

* Monthly order trends
* Monthly revenue trends
* Quarterly orders
* Yearly orders
* Orders by day of the week
* Top cities by revenue
* Revenue contribution by state
* Top restaurants
* Category-wise order volume
* Most ordered dishes
* Revenue by state
* Orders by price range
* Rating distribution
* Cuisine/category performance

## Key SQL Concepts Used

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* Aggregate functions
* `CASE`
* `JOIN`
* `CTE`
* `ROW_NUMBER()`
* Date functions
* `IDENTITY`
* Primary Keys
* Foreign Keys
* Star Schema / Dimensional Modelling

## Project Structure

```text
Swiggy-SQL-Data-Analysis/
│
├── README.md
├── Swiggy_Data_Analysis.csv
└── Swiggy_Data_Analysis.sql
```

## Objective

The objective of this project is to demonstrate practical SQL skills in **data cleaning, database design, dimensional modelling, KPI creation, and business analysis** using a real-world food delivery dataset.

## Author

**Aksayalaxme Umapathy**

M.Sc. Physics | Aspiring Data Analyst
