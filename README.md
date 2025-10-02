# task7-02.10.2025--Elevate-Labs
# TASK 7: Get Basic Sales Summary from a Tiny SQLite Database using Python

##  Project Overview

This project demonstrates how to use **SQLite with Python** to analyze a small sales dataset.
We created a **stationery sales database**, queried it using SQL, and visualized revenue by product with Pandas & Matplotlib.

##  What I Did

* Created a SQLite database `sales_data.db` with a table `sales`.
* Inserted sample stationery sales data (Pen, Pencil, Notebook, Eraser, Marker).
* Wrote SQL queries to calculate **total quantity sold** and **total revenue per product**.
* Loaded results into **Pandas DataFrame** for easy handling.
* Printed a **summary table** of sales performance.
* Plotted a **bar chart** (`stationery_sales_chart.png`) to visualize revenue by product.
* Summarized **findings, insights, and conclusions** for business perspective.

##  Tools Used

* Python (`sqlite3`, `pandas`, `matplotlib`)
* SQLite (lightweight built-in database)
* Jupyter Notebook / Python script

##  Example Output

**Sales Summary Table**

```
   product   total_qty   revenue
0   Eraser         40     120.0
1   Marker         20     500.0
2  Notebook        45    2250.0
3      Pen         70     700.0
4   Pencil        160     800.0
```

**Bar Chart:**
📊 `stationery_sales_chart.png` shows revenue by product.

##  Key Insights

* Notebooks dominate revenue due to high unit price.
* Pencils sell the most but generate less revenue.
* Premium + basic stationery mix ensures balanced sales.

