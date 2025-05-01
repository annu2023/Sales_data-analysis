# Sales_data-analysis

This repository contains the sales data analysis project performed using Python, SQLite, and data visualization techniques. The analysis focuses on extracting meaningful insights from the sales dataset using SQL queries and visualizing the results through various charts and graphs.

# Project overview

The project analyzes a sales dataset to uncover patterns, trends, and key metrics related to sales performance. The analysis includes the following steps:

    Data Import: The sales dataset is imported into a Jupyter notebook from a excel file to database source.

    SQL Queries: SQL queries are used to perform data aggregation, filtering, and summarization.

    Data Analysis: SQL queries are executed to extract specific insights, such as total sales, product-wise performance, and regional trends.

    Data Visualization: Graphs and charts are created to visualize the findings, and images are saved in .png format for easy access.

 # Technologies Used

    Python (Jupyter Notebook)

    SQL (for data querying and analysis)

    Matplotlib (for data visualization)

    Pandas (for data manipulation)

    SQLite (for querying the sales data)

  # Database Setup

    If using a database, make sure to configure the connection settings in the notebook:

    !pip install ipython-sql
    import sqlite3
    conn = sqlite3.connect("sales_data.db")
    df = pd.read_sql_query("SELECT * FROM sales", conn)

 # Graphs

   The generated graphs are saved as .png files for easy viewing. These graphs are saved in the same directory as the notebook. For example:

    monthly_sales_trends.png – Shows trends in sales over time.

    profit_by_region.png – A bar chart showing the profit by region.

    revenue_by_region.png – A bar graph comparing revenue across different regions.

    top_profitable_products.png - A bar graph showing top 5 profitable products.

    top_5_products_quantity.png - A bar chart showing top 5 products according to quantity sold .

# Files in the Repository

    `Sales_py_sql.ipynb` – Jupyter notebook containing the sales data analysis.

    `Sales_data.xlsx` - The raw data table .
    
    `sales_data.db` – The Database file created containing the sales table.

    images/ – Directory containing the saved .png files of graphs.

        `monthly_sales_trends.png`

        `profit_by_region.png`

        `revenue_by_region.png`

        `top_profitable_products.png`  

        `top_5_products_quantity.png`

  # Conclusion

    This project demonstrates how Python and SQL can be used together for in-depth data analysis. It showcases how to extract actionable insights from sales data and present them visually for easy understanding.
