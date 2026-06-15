# Online Retail Sales Analysis

## Project Overview

This project analyzes an online retail dataset to uncover sales trends, customer purchasing behavior, product performance, and revenue patterns using Python.

The analysis focuses on key business metrics such as revenue generation, order volume, product sales, customer activity, and country-wise performance.

## Objectives

- Calculate Total Revenue Generated
- Determine Total Orders Placed
- Analyze Total Products Sold
- Calculate Average Order Value
- Study Monthly Sales Trends
- Analyze Quarterly Sales Performance
- Identify Top 10 Products Sold
- Identify Top Products by Revenue
- Identify Least-Performing Products
- Analyze Customer Purchase Behavior
- Calculate Average Spending per Customer
- Analyze Customer Order Frequency
- Study Revenue by Country

## Dataset

Source: Online Retail Dataset

Columns Used:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Preparation

The dataset was loaded and explored using Pandas.

A new revenue column was created:

```python
dh['total_price'] = dh['UnitPrice'] * dh['Quantity']
```

## Analysis Performed

### Revenue Analysis

- Total Revenue Generated
- Revenue Trend Over Time

### Sales Analysis

- Total Orders Placed
- Total Products Sold
- Average Order Value
- Monthly Revenue Analysis
- Quarterly Revenue Analysis

### Product Analysis

- Top 10 Products Sold
- Top Products by Revenue
- Least-Performing Products

### Customer Analysis

- Number of Unique Customers
- Average Spending per Customer
- Customer Order Frequency

### Geographic Analysis

- Revenue by Country

## Visualizations

The project includes:

- Revenue Trend Line Chart
- Monthly Revenue Line Chart
- Quarterly Revenue Bar Chart
- Customer Frequency Chart
- Product Performance Analysis
- Country-wise Revenue Analysis

## Key Insights

- Revenue trends help identify peak sales periods.
- A small group of products contributes significantly to total revenue.
- Customer purchasing behavior reveals repeat buyers.
- Revenue distribution varies across different countries.
- Monthly and quarterly analysis helps understand seasonal business performance.

## Project Structure

Online-retail-product-project/

├── OnlineRetailAnalysis.ipynb

├── README.md

└── Dataset

## How to Run

1. Clone the repository

```bash
git clone <repository-link>
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook and run all cells.

## Author

Nandhan A S

Aspiring Data Analyst | Python | Pandas | Data Visualization

## Key Visualizations

### Monthly Revenue Trend
<img width="1021" height="522" alt="monthly_revenue" src="https://github.com/user-attachments/assets/ad354e87-ce1c-44a0-a672-b7d3ab6ab031" />



### Top 10 Products by Sales
![Top Products](top_products.png)

### Country-wise Revenue
![Country Revenue](country_revenue.png)
