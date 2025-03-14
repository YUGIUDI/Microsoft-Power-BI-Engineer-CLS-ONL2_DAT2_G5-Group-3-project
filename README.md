📊 Superstore Sales Dashboard - Power BI Project

🔹 Project Overview

This project aims to create a professional and interactive Power BI dashboard for analyzing Superstore Sales data. The dashboard provides insights into sales performance, customer behavior, regional sales trends, and shipping efficiency.

🔹 Dataset Information

Dataset Name: Superstore Sales Dataset

Number of Records: 9,800

Columns: 18

Key Fields:

Order ID, Order Date, Ship Date

Customer ID, Customer Name, Segment

Region, State, City, Postal Code

Product ID, Category, Sub-Category, Product Name

Sales, Profit, Ship Mode

🔹 Project Objectives

Analyze total sales, orders, and customer behavior.

Identify top-selling products, regions, and customer segments.

Track sales trends over time (yearly, monthly, daily).

Evaluate shipping efficiency and delivery delays.

Provide interactive filters and drill-down insights.

🔹 Key Performance Indicators (KPIs)

Total Sales = SUM(Superstore[Sales])

Total Orders = DISTINCTCOUNT(Superstore[Order ID])

Total Customers = DISTINCTCOUNT(Superstore[Customer ID])

Average Order Value (AOV) = DIVIDE([Total Sales], [Total Orders])

Sales by Region, State, and City

Top 10 Customers & Products by Sales

Profit Margin % = DIVIDE([Total Profit], [Total Sales])

Sales Growth % (YoY)

Late Shipments % = Percentage of delayed deliveries

🔹 Visualizations & Dashboard Structure

📌 Page 1: Executive Summary

KPIs: Total Sales, Orders, Customers, AOV

Sales by Region, Category, and Ship Mode

Sales Trend Over Time (Line Chart)

📌 Page 2: Sales Analysis

Sales by Region, Category, Sub-category, Customer Segment

Top-selling products and customers

Geographical Sales (Map Visual)

📌 Page 3: Customer Insights

New vs Returning Customers

Customer Lifetime Value (CLV)

Sales by Segment (Pie Chart)

📌 Page 4: Shipping & Operational Analysis

Orders by Ship Mode

Avg Shipping Time & Late Shipments %

Heatmap of Order Trends by Weekday

🔹 Power BI Features Used

Data Transformation: Power Query for cleaning and modeling

DAX Calculations: Custom measures for KPIs and trends

Visualizations: Line charts, bar charts, pie charts, treemaps, maps

Interactivity: Slicers, drill-through, bookmarks

AI Insights: Forecasting, anomaly detection, key influencers

🔹 How to Use This Project

Download the dataset and Power BI report file (.PBIX)

Load the data into Power BI Desktop

Refresh the data to see real-time updates

Interact with filters to explore insights

Publish to Power BI Service for sharing and collaboration

🔹 Future Enhancements

Add profit analysis to track high and low-margin products

Implement dynamic reports based on user input

Automate data refresh using Power BI Gateway

Develop predictive analytics using machine learning models
