Dataset
Dataset: Sample Superstore Retail Dataset
Rows: 10,194
Columns: 21
Key Features:
Order Date
Ship Mode
Segment
Region
Category
Sub-Category
Sales
Quantity
Discount
Profit
Data Quality Findings:
No missing values detected
No duplicate records identified
Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Project Workflow
1. Data Loading & Understanding
Imported and explored the dataset using:
head()
info()
describe()
shape
columns
2. Data Cleaning
Checked for missing values
Verified duplicate records
Confirmed data quality before analysis
3. Feature Engineering
Converted Order Date to datetime format
Extracted:
Year
Month
Enabled time-based trend analysis
4. Exploratory Data Analysis
Analyzed sales performance across categories
Evaluated profit performance across regions
Examined customer segments
Investigated sub-category performance
Identified loss-making transactions
Studied relationships between discounting and profitability
5. Correlation Analysis
Explored relationships among:
Sales
Profit
Discount
Quantity
6. Data Visualization
Created visualizations to communicate business insights effectively
Key Insights
Technology generated the highest total sales and profit among all categories.
The West region achieved the highest overall sales and profitability.
Chairs and Phones were among the highest-performing sub-categories by sales.
Sales reached their peak during November, while profit peaked in December.
The Consumer segment contributed the largest share of total sales.
Higher discount levels were associated with lower profitability.
Several products generated negative profit despite strong sales performance, highlighting potential inefficiencies in discounting strategies.
Visualizations Included
Sales by Category (Bar Chart)
Profit by Category (Bar Chart)
Profit by Region (Bar Chart)
Sales by Customer Segment (Bar Chart)
Monthly Sales Trend (Line Chart)
Sales by Sub-Category (Horizontal Bar Chart)
Discount vs Profit (Scatter Plot)
Correlation Heatmap
Conclusion

This project demonstrates how exploratory data analysis can transform raw retail transaction data into actionable business insights. By combining data cleaning, statistical exploration, and visualization techniques, key patterns in sales, profitability, customer behavior, and discounting strategies were identified to support data-driven decision-making.
