# Business Sales performance

## Project Overview
This project analyzes online retail transaction data to uncover useful business insights. 
The analysis focuses on understanding revenue trends, identifying top-selling products, 
examining regional sales performance, and analyzing product category performance.
Using Python data analysis libraries, the dataset was cleaned, processed, and explored 
to identify patterns in sales and customer purchasing behavior. The results are 
presented through clear visualizations such as line charts and bar charts.
The goal of this project is to demonstrate how data analytics can transform raw sales 
data into meaningful insights that support business decision-making.



## Project Objectives

The objectives of this project are:

- Clean and preprocess raw retail sales data
- Calculate total revenue generated from transactions
- Identify top-performing products
- Analyze monthly sales trends
- Examine sales distribution across regions
- Explore product category performance
- Present insights using visualizations



## Dataset Description

The dataset used in this project is the **Online Retail Dataset**, which contains 
transaction records from an online retail store.
Each row in the dataset represents a single purchase transaction.

### Dataset Columns

| Column | Description |
|------|------|
| InvoiceNo | Unique invoice number for each transaction |
| StockCode | Unique product code |
| Description | Product name |
| Quantity | Number of units purchased |
| InvoiceDate | Date and time of the transaction |
| UnitPrice | Price per unit |
| CustomerID | Unique identifier for each customer |
| Country | Customer's country |



## Tools and Libraries Used

This project was implemented using Python and the following libraries:

- **Pandas** – Data cleaning and manipulation  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical visualizations  
- **OpenPyXL** – Reading Excel files



## Data Cleaning Process
Several steps were performed to ensure the dataset was accurate and reliable.

### Removing Cancelled Transactions
Invoices beginning with **"C"** represent cancelled transactions. These were removed 
because they do not represent completed sales.

### Handling Missing Values
Rows with missing **CustomerID** values were removed to maintain data integrity.

### Removing Duplicate Rows
Duplicate rows were removed to avoid double counting transactions, which could 
distort the analysis results.

### Creating Revenue Column
A new column called **Revenue** was created using the formula:
This column represents the total value generated from each transaction.



## Data Analysis

### Monthly Revenue Trend
A line chart was created to visualize how revenue changes over time. 
This helps identify seasonal trends and variations in sales performance.

### Top 10 Selling Products
A bar chart was used to identify the products with the highest total quantity sold. 
This helps understand customer demand and product popularity.

### Sales by Region
Sales were grouped by country to determine which regions generate the most revenue.

### Sales by Category
Products were grouped into simplified categories to analyze how different product 
groups contribute to total revenue.



## Key Insights
The analysis revealed several important findings:

- Revenue varies across different months
- A few products generate a large portion of sales
- Some countries contribute the majority of revenue
- Certain product categories outperform others

These insights can help businesses improve inventory management, marketing strategies, 
and market expansion decisions.



## Skills Demonstrated
This project demonstrates:

- Data cleaning and preprocessing
- Exploratory data analysis
- Data visualization
- Business insight generation
- Python data analytics workflow



## Author

**Sereya Nchoe**


