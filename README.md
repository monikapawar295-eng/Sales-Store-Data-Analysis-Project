Sales Store Data Analysis Project

An End-to-End SQL Server Data Analytics Project


📖 Project Overview

The Sales Store Data Analysis Project uses SQL Server to clean, process, and analyze retail sales data.
It transforms raw transactional records into actionable business insights through data import, validation, and analysis.
This project demonstrates practical SQL skills such as data modeling, bulk import, data cleaning, and business intelligence reporting for better decision-making.

🎯 Project Objectives

Import and clean raw sales data using SQL Server

Handle duplicates, NULLs, and inconsistent values

Standardize and validate key data fields

Analyze sales trends, customer behavior, and product performance

Generate insights to support business and marketing strategies

🛠️ Tools & Technologies Used

Microsoft SQL Server Management Studio (SSMS)

T-SQL (DDL, DML, Aggregate Functions, CTEs)

BULK INSERT for dataset import

Microsoft Excel / CSV Dataset

Retail E-commerce Sales Data

🧩 Database Design Overview

Table Name: Sales_store

Column Name	Description
transaction_id	Unique transaction number
customer_id	Unique customer identifier
customer_name	Customer’s full name
customer_age	Age of the customer
gender	Gender of the customer
product_id	Unique product identifier
product_name	Product name
product_category	Category of the product
quantity	Quantity purchased
price	Product price
payment_mode	Payment method used
purchase_date	Date of purchase
time_of_purchase	Time of the transaction
status	Order status (Completed/Cancelled)

🧹 Data Cleaning Steps

Removed duplicate records using ROW_NUMBER()

Fixed column headers (e.g., quantiy → quantity, prce → price)

Checked and handled NULL values

Standardized entries for gender and payment mode

Ensured valid data types for all columns

📊 Key Insights / Findings

Top-selling products and high-value customers

Most frequently cancelled products

Peak sales times (Morning, Afternoon, Evening)

High-revenue product categories

Most used payment methods

Age-based buying patterns

Monthly sales trends and performance

💡 Business Impact

Improved understanding of customer behavior and demand

Enhanced marketing and promotion strategies

Streamlined payment and inventory management

Supported data-driven decision-making for growth

🏁 Conclusion

This end-to-end SQL project highlights the power of data analytics in the retail domain.
By converting raw sales data into insights, it helps businesses optimize product strategy, marketing, and operations, driving overall efficiency and customer satisfaction.
