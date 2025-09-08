# Finance SQL Analytics Project

## Overview
This project demonstrates **advanced SQL analytics techniques** applied to financial sales data. It includes **user-defined functions, joins, stored procedures, and reporting** to analyze customer and product sales.  

The purpose is to showcase **SQL skills in a real-world finance scenario**, which is highly relevant for roles like **Data Analyst, Business Analyst, or SQL Developer**.

---

## Skills Demonstrated
- Writing **User-Defined SQL Functions**
- Performing **Joins and Aggregations**
- Writing **Stored Procedures**
- Financial Data Analysis & Reporting
- Business-level Insights (Market Badge, Sales Trends)

---

## Repository Structure

## Repository Structure

- **Finance-SQL-Analytics/**
  - `README.md`
  - **screenshots/** (Query result screenshots)
    - `customer_query.jpg`
    - `monthly_product_sales.jpg`
    - `total_monthly_sales.jpg`
    - `get_monthly_gross_sales_for_customer.jpg`
    - `get_market_badge.jpg`
  - **SQL_Scripts/** (SQL scripts by module)
    - `01_User_Defined_Functions.sql`
    - `02_Gross_Sales_Report_Monthly.sql`
    - `03_Total_Sales_Report.sql`
    - `04_Stored_Procedures_Monthly_Gross.sql`
    - `05_Stored_Procedure_Market_Badge.sql`
  - **Docs/** (Optional explanations)
    - `Project_Explanation.md`
  - **Data/** (Optional sample data)
    - `sample_data.sql`



---

## Modules

### 1. User-Defined SQL Functions
- Fetch customer codes for a specific market
- Create function `get_fiscal_year()` to calculate fiscal year dynamically
- Demonstrate usage of the function in queries  

**Screenshot:**  
![Customer Query](screenshots/customer_query.jpg)

---

### 2. Gross Sales Report: Monthly Product Transactions
- Join sales data with product table
- Calculate monthly gross sales per product
- Include `gross_price` calculations  

**Screenshot:**  
![Monthly Product Sales](screenshots/monthly_product_sales.jpg
)

---

### 3. Gross Sales Report: Total Sales Amount
- Aggregate monthly sales for a specific customer
- Demonstrates `SUM()` and grouping for reporting  

**Screenshot:**  
![Total Sales Amount](screenshots/total_monthly_sales.jpg)

---

### 4. Stored Procedures: Monthly Gross Sales Report
- Reusable procedure to generate monthly gross sales for any customer(s)
- Demonstrates **dynamic input handling** with `FIND_IN_SET()`  

**Screenshot:**  
![Stored Procedure Demo](screenshots/get_monthly_gross_sales_for_customer.jpg
)

---

### 5. Stored Procedure: Market Badge
- Procedure to assign “Gold” or “Silver” badge to a market
- Demonstrates conditional logic and **OUT parameters** in SQL  

**Screenshot:**  
![Market Badge Demo](screenshots/get_market_badge.jpg)

---


