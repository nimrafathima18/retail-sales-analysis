# Retail Sales Analysis

## Project Overview
This project focuses on analyzing retail transaction data to uncover insights about customer purchasing behavior, sales trends, and product performance. The goal is to use data analysis and visualization techniques to help businesses understand their sales patterns and make data-driven decisions.

The analysis was performed using Python and common data science libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

---

## Dataset
The dataset used in this project is the Online Retail Dataset, which contains transactional data from an online retail store.

Main columns in the dataset include:

- InvoiceNo – Unique invoice number for each transaction  
- StockCode – Product code  
- Description – Product description  
- Quantity – Number of items purchased  
- InvoiceDate – Date and time of the transaction  
- UnitPrice – Price per unit of the product  
- CustomerID – Unique customer identifier  
- Country – Country where the customer resides  

Dataset Source:  
UCI Machine Learning Repository – Online Retail Dataset

---

## Data Cleaning
Before performing the analysis, several preprocessing steps were applied:

- Removed missing values in important columns
- Removed cancelled transactions
- Converted date columns to datetime format
- Removed negative quantities and invalid records
- Created new calculated columns, such as TotalPrice

Example feature created:

TotalPrice = Quantity × UnitPrice

---

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to identify patterns and trends in the retail data.

Some key analyses include:

- Sales distribution analysis
- Top-selling products
- Country-wise sales comparison
- Monthly sales trends
- Customer purchase behavior

Visualization techniques used:

- Bar charts
- Histograms
- Scatter plots
- Line charts

---

## Key Insights
Some important insights obtained from the analysis include:

- Certain products contribute significantly to overall revenue.
- Sales show strong seasonal patterns across months.
- A small group of customers contributes to a large portion of total sales.
- Some countries generate significantly higher revenue than others.

These insights can help businesses improve marketing strategies and inventory planning.

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Project Workflow

1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis  
4. Data Visualization  
5. Insight Generation  

---

## Conclusion
Retail sales analysis helps businesses understand customer purchasing patterns and product demand. By analyzing transaction data, companies can identify high-performing products, seasonal sales trends, and valuable customer segments, enabling better decision-making and improved business strategies.

---

## Author
Fathima
