# 03_Total_Sales_Report.sql

## Purpose
Aggregates sales at a higher level to show **total monthly sales** for a customer, demonstrating SQL **aggregation functions** and **grouping**.

## Explanation of Queries

1. **Sum gross sales by month**  
   Uses `SUM()` and `ROUND()` to calculate total sales per month.

2. **Group by date**  
   Prepares the dataset for monthly reporting or visualization.

## SQL Code

```sql
-- Generate monthly gross sales report for Croma India for all the years
SELECT 
    s.date, 
    SUM(ROUND(s.sold_quantity * g.gross_price, 2)) AS monthly_sales
FROM fact_sales_monthly s
JOIN fact_gross_price g
    ON g.fiscal_year = get_fiscal_year(s.date)
   AND g.product_code = s.product_code
WHERE customer_code = 90002002
GROUP BY date;
```

## Screenshot##

 **Total_Sales_Report:** ![Total_Sales_Report](screenshots/total_monthly_sales.jpg)
