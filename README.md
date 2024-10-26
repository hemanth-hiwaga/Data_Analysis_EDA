## Case Study: E-commerce Sales Analysis

### Project Overview
As part of my journey to become a proficient data analyst, I undertook an e-commerce sales analysis project. The objective was to gain insights into sales performance, identify key trends, and provide actionable business recommendations based on data-driven findings.

### 1. Data Collection and Familiarization
**Objective**: Load the sales data and understand its structure.  
**Steps**:
- I loaded the dataset from the specified path.
- To understand the dataset, I used methods like `info()`, `describe()`, and `columns`.
- This gave me a clear view of data types, missing values, and overall data distribution.

### 2. Data Cleaning
**Objective**: Clean the data for accurate analysis.  
**Steps**:
- Removed unnecessary columns like `Unnamed: 0`.
- Stripped whitespace from the 'City' names to standardize the data.
- Handled null values and duplicates to ensure data integrity.
- Converted 'Order Date' to datetime format.
- Extracted additional columns such as `year`, `Month_Name`, `week`, and `Total_Sales`.

### 3. Exploratory Data Analysis (EDA)
**Objective**: Understand data distribution and identify patterns.  
**Steps**:
- Summarized the data using the `describe()` method.
- Visualized distributions with histograms and box plots.
- This helped in identifying data patterns and potential anomalies.

### 4. Monthly Sales Analysis
**Objective**: Analyze sales trends by month.  
**Steps**:
- Grouped and summed sales by `Month_Name`.
- Visualized monthly sales using a bar plot.
- This revealed peak sales periods and seasonal trends.
 
 ![plot](/images/1_1_sales-by-each-month.png)

### 5. Hourly Sales Analysis
**Objective**: Analyze sales trends by hour of the day.  
**Steps**:
- Grouped and summed sales by `Hour`.
- Visualized hourly sales using a horizontal bar plot.
- This highlighted the most active sales hours.

![](/images/1_2_sales-by_hour.png)

### 6. Top 5 Products Analysis
**Objective**: Identify and visualize top-selling products monthly.  
**Steps**:
- Created a pivot table for monthly sales by product.
- Identified the top 5 products.
- Visualized monthly sales for each top product using subplots.
- This provided insights into product performance over time.

![](/images/1_3_top5-products-monthly-sales.png)

### 7. City Sales Analysis
**Objective**: Analyze total sales by city.  
**Steps**:
- Grouped and summed sales by `City`.
- Visualized city sales using a horizontal bar plot.
- This showed which cities generated the most revenue.

![](/images/2_1_sales_by_city.png)

### 8. Product Sales in Cities
**Objective**: Analyze sales distribution of each product across different cities.  
**Steps**:
- Created a pivot table for product sales by city.
- Visualized product sales in cities using subplots.
- This helped in understanding regional product preferences.

![](/images/2_2_product_sales_in_cities_loop.png)

### 9. City-wise Product Sales Analysis
**Objective**: Analyze sales for each city by product.  
**Steps**:
- Transposed and sorted the pivot table for product sales by city.
- Visualized sales for each city using subplots.
- This provided a detailed view of product performance in each city.

![](/images/2_3_for-each-city-product-sales.png)

### 10. Heatmap of Product Sales by City
**Objective**: Visualize the correlation of sales between products and cities.  
**Steps**:
- Created a pivot table for product sales by city.
- Visualized the correlation using a heatmap.
- This highlighted strong sales relationships between products and cities.

![](/images/2_4_heatmap_produt_city.png)

### Case 11: Product Sales Analysis

This analysis involves grouping data by 'Product' and summarizing 'Quantity Ordered' and 'Total Sales'. By creating subplots for each column, we visualize sales performance for individual products. The sorted bar plots highlight top-performing products, enabling clear insights into sales distribution. This visualization aids in identifying key products driving revenue.

![](/images/4_1_salesAndQuantity.png

### Summary
This case study provided a detailed analysis of e-commerce sales data, exploring trends by month, hour, city, and product. Each step was carefully documented to ensure clarity and reproducibility, offering valuable insights into sales performance and customer behavior. The visualizations enhanced the storytelling aspect, making it easier to communicate findings and support decision-making.

---
