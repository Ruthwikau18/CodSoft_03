📊 Sales Analytics Dashboard — CodSoft Task 3
📌 Project Overview

This project is completed as Task 3 of the CodSoft Data Analytics Internship. The objective is to create meaningful visualizations and an interactive dashboard to analyze sales data, identify trends, understand relationships between variables, and present insights clearly.

The dashboard was developed using Power BI, with DAX measures used for KPI calculations and interactive analysis.

🎯 Objectives
Analyze sales performance using visualizations.
Understand sales trends over time.
Compare sales across different categories.
Analyze customer segments.
Identify top-performing products.
Analyze regional sales performance.
Compare sales and profit relationships.
Create an interactive Power BI dashboard.
Present important business insights clearly.
🛠️ Technologies Used
Power BI
DAX
Microsoft Excel / CSV
Python & Google Colab for data analysis
Matplotlib
Seaborn
Pandas
📂 Dataset

The dataset contains sales-related information including:

Column	Description
Category	Product category
Order Date	Date of the order
Product	Product name
Profit	Profit generated
Quantity	Quantity sold
Region	Sales region
Sales	Sales amount
Segment	Customer segment
📊 Dashboard Visualizations

The Power BI dashboard includes:

1. KPI Cards

Displays important metrics such as:

Total Sales
Total Profit
Total Quantity
Average Sales
2. Monthly Sales Trend

A line chart showing how sales change across the months.

3. Sales vs Profit Analysis

A scatter chart used to understand the relationship between sales and profit across product categories.

4. Sales by Customer Segment

A column chart comparing sales across:

Consumer
Corporate
Enterprise
5. Sales by Category

A column chart showing sales performance of:

Electronics
Furniture
Accessories
6. Top Products by Sales

A bar chart highlighting the products with the highest sales.

7. Sales by Region

A donut chart showing the contribution of different regions to total sales.

8. Interactive Slicers

The dashboard contains slicers that allow users to filter the analysis by:

Category
Segment
Order Date / Year
🧮 DAX Measures

Some of the measures created for the dashboard include:

Total Sales =
SUM(sales_data[Sales])
Total Profit =
SUM(sales_data[Profit])
Total Quantity =
SUM(sales_data[Quantity])
Average Sales =
AVERAGE(sales_data[Sales])
🔍 Key Insights

The dashboard helps identify:

Which category generates the highest sales.
Which customer segment contributes the most revenue.
Which products are top performers.
How sales vary across different regions.
Monthly sales trends.
The relationship between sales and profit.
Overall sales and profitability performance.
🎨 Dashboard Features
Interactive visualizations
KPI cards
Bar charts
Column charts
Line charts
Scatter plots
Donut charts
Interactive slicers
DAX-based calculations
Consistent formatting
Easy-to-understand layout
📁 Project Structure
Sales-Analytics-Dashboard/
│
├── sales_data.csv
├── Sales_Analytics_Dashboard.pbix
├── README.md
└── screenshots/
    └── dashboard.png
🚀 How to Use
Download or clone this repository.
Open Sales_Analytics_Dashboard.pbix using Power BI Desktop.
If required, update the dataset location.
Click Refresh to load the latest data.
Use the slicers to interact with the dashboard.
Explore the charts and KPIs to understand the sales performance.
💡 Conclusion

This project demonstrates how Power BI, DAX, and data visualization techniques can be used to transform raw sales data into an interactive dashboard. The dashboard makes it easier to identify sales patterns, compare business segments, analyze products and regions, and communicate important insights effectively.

🏆 Internship

CodSoft — Data Analytics Internship

Task 3: Data Visualization & Interactive Dashboard
