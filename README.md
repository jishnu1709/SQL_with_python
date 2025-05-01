# SQL_with_python
This project demonstrates how to create and analyze a simple sales database using SQLite and Python. It includes generating synthetic sales data, storing it in a database, and performing SQL-based analysis, followed by data visualization using pandas and matplotlib.

📁 Project Structure
graphql
Copy
Edit
sales_analysis/
├── sales_db.sqlite        # SQLite database file (auto-generated)
├── sales_analysis.py      # Python script with data generation, SQL queries, and visualization
└── README.md              # Project documentation
📌 Features
Create a SQLite database (sales_db.sqlite) with a Sales table.
Insert 10 sample rows with random customer names and product data.
Products: Shirt (P001), Pants (P002), Jeans (P003)
SQL query to calculate:
Total Sales (count)
Total Quantity Sold
Total Revenue (Quantity * Price)
Visualize total revenue by product using a bar chart.
