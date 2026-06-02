Superstore Sales EDA
Exploratory data analysis of the Sample Superstore retail dataset using Python. The project cleans and explores 10,000+ orders to uncover patterns in sales, profit, regional performance, customer segments, and the impact of discounting — turning raw transaction data into actionable business insights.
Dataset

Source: Sample Superstore retail dataset
Size: 10,194 rows × 21 columns
Key fields: Order Date, Ship Mode, Segment, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit
Quality: No missing values and no duplicate rows were found during cleaning.

Tools & Libraries

Python
Pandas — data loading, cleaning, aggregation
NumPy — numerical operations
Matplotlib & Seaborn — data visualization

Workflow

Data loading & inspection — head(), info(), describe(), shape, and column review.
Data quality checks — verified there were no null values or duplicate records.
Feature engineering — converted Order Date to datetime and extracted year and month for time-based analysis.
Aggregation & grouping — summarized sales and profit across categories, sub-categories, regions, segments, and months.
Correlation analysis — examined relationships between Sales, Profit, Discount, and Quantity.
Visualization — built charts to communicate the findings clearly.

Key Insights

Technology is the strongest category, leading in both total sales and profit.
The West region generates the highest sales and the highest profit.
Chairs and Phones are among the top-performing sub-categories by sales.
Sales peak in November, while profit peaks in December, pointing to seasonal demand.
The Consumer segment contributes the most sales.
Higher discounts are associated with lower profit — and several products are sold at a loss, highlighting clear opportunities to review the discounting strategy.

Visualizations

Sales by Category (bar)
Profit by Category (bar)
Profit by Region (bar)
Sales by Customer Segment (bar)
Monthly Sales Trend (line)
Sales by Sub-Category (horizontal bar)
Discount vs Profit (scatter)
Correlation Heatmap (Sales, Profit, Discount, Quantity)
