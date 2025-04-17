# Task 7: Basic Sales Summary from SQLite Using Python

## 📌 Objective
This task focuses on extracting simple sales insights from a small SQLite database using Python. The goal is to practice combining SQL queries with Python tools such as Pandas and Matplotlib to generate meaningful summaries and visualizations.

---

## 🧰 Tools & Technologies
- Python
- SQLite (`sqlite3`)
- Pandas
- Matplotlib
- Jupyter Notebook / Python Script

---

## 🗃 Dataset
A mock dataset of 50 sales records was created with the following fields:
- `id`: Unique transaction ID
- `date`: Date of sale
- `product`: Product name
- `quantity`: Quantity sold
- `price`: Price per unit

---

## 🧪 Steps Performed
1. **Database Setup**: Created and connected to `sales_data.db`.
2. **Table Creation & Data Insertion**: Inserted 50 records into the `sales` table.
3. **Data Querying**: Queried total quantity and revenue per product using SQL.
4. **Data Loading**: Loaded results into a Pandas DataFrame.
5. **Visualization**:
   - Created a bar chart of total revenue by product.
   - Sorted products by revenue.
   - Highlighted the top-selling product in red.

---

## 📊 Output
- Printed sales summary table in the console.
- Displayed a clean bar chart showing product-wise revenue.
- Enhanced readability using labels, colors, and sorting.

---

## ✅ Learnings
- How to use `sqlite3` to interact with an SQLite database in Python.
- How to run SQL queries and import results using Pandas.
- How to visualize data insights using Matplotlib.
- Basics of data storytelling through charts.

---

## 📁 Files
- `sales_data.db`: SQLite database containing sales records.
- `task7_sales_summary.py` or `.ipynb`: Python script/notebook performing the analysis.
- `README.md`: This documentation.

---

