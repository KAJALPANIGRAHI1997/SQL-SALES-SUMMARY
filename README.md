# SQLite Sales Summary with Python
Python + SQLite project to calculate total quantity, price, revenue, and profit from a sales dataset, with results visualized using Matplotlib.
## 📌 Overview
This project demonstrates how to:
- Load an Excel dataset into a SQLite database
- Use SQL queries inside Python to calculate:
  - Total quantity sold
  - Product price
  - Total revenue
  - Profit
- Display results using **pandas** and visualize with **Matplotlib**.

## 🛠 Tools & Libraries
- Python 3.x
- SQLite (built-in with Python)
- pandas
- matplotlib
- openpyxl (for reading Excel)

## 📂 Dataset
The dataset contains product inspection details including:
- Product Name
- Units Checked
- Other inspection-related columns

Price, total revenue, and profit are calculated in the SQL query.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/sqlite-sales-summary.git
   cd sqlite-sales-summary

2. Install required libraries:

pip install pandas matplotlib openpyxl


3. Place your dataset file (e.g., Modified_Quality_Inspection_Dataset.xlsx) in the project folder.

Run the Python script:

python sales_summary.py

## 📊 Output

Console: Prints the aggregated summary table

Chart: Generates a bar chart (sales_chart.png) showing total revenue per product

Example summary:

product	total_qty	price	total_revenue	profit
Module-Y	425	150	63,750	19,125
Modul-X	540	200	108,000	32,400
## 🎯 Learning Outcomes

How to create and connect to a SQLite database in Python

Writing SQL queries inside Python scripts

Performing data aggregation

Creating basic visualizations with Matplotlib

## Author: Kajal Panigrahi
## License: MIT
