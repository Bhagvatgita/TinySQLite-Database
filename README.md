# TinySQLite-Database

# Basic Sales Summary from a Tiny SQLite Database using Python.

## Objective
Use SQL inside Python to pull simple sales info (total quantity sold, total revenue), and display it using print statements and a basic bar chart.

##  Tools Used
- Python
- SQLite (built-in)
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset
A small sales_data.db SQLite file created using Python containing:
- Product name
- Quantity
- Price

##  What It Does
- Creates a SQLite database with dummy sales records
- Runs SQL queries to summarize:
  - Total quantity sold per product
  - Total revenue per product
- Loads SQL results into a Pandas DataFrame
- Prints results and displays a bar chart for revenue per product

## Output
### Console Output:
product total_qty revenue
0 Shampoo 15 2250.0
1 Soap 30 1200.0
2 Toothpaste 15 900.0

### Chart:
A bar chart showing Revenue by Product using matplotlib.
## How to Run
1. Install libraries:  
pip install pandas matplotlib
2. Run the Python script or Jupyter Notebook.
The script:
Creates the database
Queries the sales data
Prints results
Displays bar chart

## What I have learned

I have learned to create and connect to a SQLite database using Python. 
Also learned how to write real SQL query inside python like group data by product, calculate total quantity sold and calculate total revenue.
Learned how to inspect and print structured data in tabular format.
Used matplotlib to plot bar charts that show revenue by product. Also below key concepts Practiced: QL fundamentals: SUM(), GROUP BY
Python-SQL integration using sqlite3
Data analysis using pandas
Basic data visualization using matplotlib
How databases and code work together in real-world projects
