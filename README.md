# TASK7
📊 Sales Summary Analysis – Using SQL, Python & Power BI

Internship Task – Data Analyst Role

This project performs a basic sales data analysis using SQL, Python, and Power BI.
The workflow includes loading data, running SQL queries, visualizing results, and creating a dashboard.


---

🧾 1. Project Overview

The purpose of this task is to analyze sales data from a small dataset and generate:

Total quantity sold

Total revenue

Revenue by product

Quantity by product

Bar charts and summary tables

A Power BI dashboard visualizing the results



---

🗂 2. Tools & Technologies

Oracle SQL Developer 

Power BI Desktop

CSV for exporting data

---

🧮 3. SQL Queries Used

SELECT 
    product,
    SUM(quantity) AS total_qty,
    SUM(quantity * price) AS revenue
FROM sales_data
GROUP BY product;

This query calculates total quantity and revenue for each product.

📈 Power BI Dashboard

Dashboard includes:

✔ KPI Cards

Total Revenue

Total Quantity Sold

Number of Products


✔ Bar Chart

Revenue by Product


✔ Column Chart

Quantity by Product


✔ Summary Table

Product-wise revenue and quantity


✔ Slicers

Product filter

Price filter
