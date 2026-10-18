## Project Documentation

![Project Page 2](E-commerce-page-2.png)
# 🛒 E-Commerce Sales Analysis

## 📌 Project Overview

This project focuses on analyzing e-commerce sales data using Python. The main purpose is to understand sales performance, profitability, product categories, customer segments, and monthly business trends through data analysis and interactive visualizations.

The project uses the Sample Superstore dataset, which contains order details, customer information, product categories, sales, quantity, discounts, and profit.

## 🎯 Project Objectives

The main objectives of this project are:

- Calculate monthly sales and identify the highest and lowest sales months.
- Analyze sales performance by product category.
- Compare sales across different product sub-categories.
- Calculate monthly profit and identify the month with the highest profit.
- Analyze profit by category and sub-category.
- Compare sales and profit across customer segments.
- Calculate and analyze the sales-to-profit ratio.

## 📂 Dataset Information

**Dataset:** Sample Superstore

The dataset contains **9,994 rows and 21 columns**.

Important columns include:

- `Order ID` – Unique order identifier.
- `Order Date` – Date when the order was placed.
- `Ship Date` – Date when the order was shipped.
- `Ship Mode` – Shipping method.
- `Customer Name` – Name of the customer.
- `Segment` – Customer segment.
- `Category` – Product category.
- `Sub-Category` – Product sub-category.
- `Sales` – Sales amount.
- `Quantity` – Number of items ordered.
- `Discount` – Discount applied to the order.
- `Profit` – Profit earned from the order.

## 🛠️ Tools and Technologies

- **Python** – Data analysis and calculations.
- **Pandas** – Data loading, cleaning, grouping, and aggregation.
- **Plotly Express** – Interactive charts and visualizations.
- **Plotly Graph Objects** – Custom and comparative charts.
- **Jupyter Notebook** – Writing and executing Python code.
- **CSV** – Dataset format.

## 🔍 Project Workflow

### 1. Data Loading and Exploration

The dataset is imported using Pandas. Initial exploration is performed using `head()`, `describe()`, and `info()` to understand the structure, data types, and statistical summary.

### 2. Data Type Conversion

The `Order Date` and `Ship Date` columns are converted into datetime format to support date-based analysis.

### 3. Feature Engineering

New columns are created from the order date:

- Order Month
- Order Year
- Order Day of Week

These columns help analyze monthly and yearly sales patterns.

### 4. Monthly Sales Analysis

Monthly sales are calculated by grouping the data by order month. A line chart is created to compare sales across the months.

### 5. Sales Analysis by Category

Total sales are calculated for Furniture, Office Supplies, and Technology. A donut chart is used to compare category-wise sales.

### 6. Sales Analysis by Sub-Category

Sales are grouped by sub-category and visualized using a bar chart to compare product performance.

### 7. Monthly Profit Analysis

Monthly profit is calculated by grouping the data by order month. A line chart helps identify monthly profit trends.

### 8. Profit Analysis by Category and Sub-Category

Profit is aggregated by product category and sub-category to compare profitability across products.

### 9. Sales and Profit by Customer Segment

Sales and profit are compared across the Consumer, Corporate, and Home Office segments using grouped data and bar charts.

### 10. Sales-to-Profit Ratio

The sales-to-profit ratio is calculated for each customer segment to compare sales amounts with the corresponding profit.

## 📊 Key Findings

Based on the analysis performed in the notebook:

- **Technology** recorded the highest total sales among the three product categories.
- **Furniture** recorded the lowest total profit among the three categories.
- **Office Supplies** generated more total profit than Furniture and Technology's category-level profit comparison.
- **December** recorded the highest monthly profit in the displayed results.
- **November** recorded the highest monthly sales in the displayed results.
- The **Consumer** segment had the highest sales-to-profit ratio, approximately 8.66.
- The **Home Office** segment had the lowest sales-to-profit ratio, approximately 7.13.

## 📈 Visualizations

The project includes interactive visualizations created using Plotly:

- Monthly Sales Analysis — Line Chart
- Sales Analysis by Category — Donut Chart
- Sales Analysis by Sub-Category — Bar Chart
- Monthly Profit Analysis — Line Chart
- Profit Analysis by Category — Donut Chart
- Profit Analysis by Sub-Category — Bar Chart
- Sales and Profit Analysis by Customer Segment — Bar Chart

These visualizations make it easier to understand sales patterns and compare business performance.

## 💡 Business Insights

This analysis can help a business:

- Identify products and categories contributing the most sales.
- Understand monthly sales and profit trends.
- Compare customer segment performance.
- Evaluate the relationship between sales and profit.
- Make more informed decisions about product sales and business strategy.

## 🚀 How to Run This Project

1. Download or clone this repository.
2. Make sure Python is installed on your computer.
3. Install the required libraries:

   ```bash
   pip install pandas plotly jupyter
   ```

4. Keep the CSV dataset in the same folder as the Jupyter Notebook.
5. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open the project notebook and run the cells in order.

## 📁 Project Files

- `Sample - Superstore (2).csv` — Dataset used for analysis.
- `E Commercee sales analysis code(1).pdf` — Exported project code and analysis.
- `E-commerce_sales_analysis.pdf` — Project overview and analysis requirements.
- `README.md` — Project documentation.

*Note: If you upload the actual `.ipynb` notebook to GitHub, include its filename in this section as well.*

## 🎓 Learning Outcomes

Through this project, I practiced data loading, exploratory data analysis, date-time conversion, feature engineering, grouping and aggregation, business metrics, and interactive data visualization using Python.

## 👨‍💻 Author

**Subhan Khan**

Aspiring Data Analyst | Python | Pandas | Data Visualization
