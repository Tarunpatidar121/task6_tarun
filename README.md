# task6_tarun

*Tools Used
- SQL 
- SQL functions: EXTRACT(), SUM(), COUNT(DISTINCT), GROUP BY, ORDER BY
📁 Dataset Overview
- Table Name: orders
- Columns:
- order_id
- order_date
- amount
- product_id
  * Approach
- Extract month and year from order_date using EXTRACT().
- Group data by year and month.
- Calculate:
- Monthly revenue using SUM(amount)
- Monthly order volume using COUNT(DISTINCT order_id)
- Sort results chronologically using ORDER BY.
- Limit results to specific time periods if needed.
  * Output
A results table showing:
- Year
- Month
- Total Revenue
- Total Orders
