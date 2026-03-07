# Retail Sales Analysis & Customer Segmentation

## Overview
This project analyzes retail sales data from the Superstore dataset to understand business performance and customer purchasing behavior. Customer segmentation was performed using **RFM analysis and K-Means clustering** to identify different customer groups.

---

## Tools
- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Power BI

---

## Exploratory Data Analysis
Performed EDA using Python to understand sales distribution and product performance.

- Aggregated sales by **product category** using Pandas  
- Visualized category-wise sales using **Seaborn bar plots**  
- Explored dataset structure and prepared data for segmentation  

---

## Customer Segmentation
Customer segmentation was performed using **RFM analysis and K-Means clustering**.

RFM features used:

- **Recency** – Days since last purchase  
- **Frequency** – Number of purchases  
- **Monetary** – Total spending  

Customers were grouped into four segments:

- Low Value Customers  
- Medium Value Customers  
- High Value Customers  
- VIP Customers  

The segmented dataset was exported as **customer_segments.csv** and used in Power BI.

---

## Dashboards

### Sales Dashboard
- Sales by Region
- Sales by Category
- Sales by Sub-category
- Sales by Segment
- Monthly Sales Trends
- Monthly Profit Trends

### Customer Segmentation Dashboard
- Sales contribution by customer segment  
- Customer purchase frequency  
- Customer lifetime value (CLV)

---

## Project Structure

dataset  
 SuperStore_Sales_Dataset.csv  
 customer_segments.csv  

notebooks  
 customer_segmentation.ipynb  

dashboard  
 Retail Sales Analysis & Customer Segmentation.pbix
