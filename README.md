# Supermarket-sales-analysis

🛒 Supermarket Sales Analysis
📌 Project Overview
This project involves analysing three months of supermarket sales data to uncover key business insights. The dataset includes detailed transaction records from a supermarket chain, covering multiple branches, product lines, and customer segments.
Dataset Source: [Kaggle – Supermarket Sales Dataset]
Timeframe: January to March 2019
Goal: To identify sales trends, customer behaviour, and product performance to support data-driven decision-making.

🎯 Objectives
The primary questions explored in this analysis include:

Which branch has the highest total sales?

Do loyalty members spend more than non-members?

Which product category generates the most profit?

How do customer ratings vary by product line?

Is there a difference in sales by gender or day of the week?

🗃️ Data and Tools
Dataset Description:

Records: 1,000 sales transactions

Each record includes:

Invoice ID

Branch (A, B, C)

Customer type (Member/Normal)

Gender

Product line (e.g., Food and beverages, Health and beauty)

Unit price

Quantity

Tax and total amount

Date and Time

Payment method

Rating

Tools Used:

Python (Jupyter Notebook)

pandas – Data handling and manipulation

matplotlib & seaborn – Visualisations

NumPy – Statistical computations

🔍 Analysis Steps
Data Loading: Imported CSV into pandas dataframe

Data Cleaning: Checked for missing values, correct data types

Branch Sales Analysis: Aggregated sales by branch using groupby

Customer Type Comparison: Compared the total and average spending of members vs non-members

Product Line Insights: Evaluated sales and ratings per category

Gender & Day Trends: Explored spending patterns across gender and weekdays

Rating Analysis: Calculated average ratings per branch and product line

Payment Method Breakdown: Visualised preference for cash, card, or eWallet

📊 Visualisations and Key Findings
1. 📍 Sales by Branch
Chart: Bar plot of total sales per branch

Insight:
Branch C had the highest total sales at $X, indicating it's the top-performing location.

2. 👥 Customer Type Spending
Chart: Boxplot comparing total spending of Members vs Non-members

Insight:
Loyalty Members tend to spend more per transaction, showing the value of retention strategies.

3. 🧴 Profit by Product Line
Chart: Pie chart of sales by product line

Insight:
The "Health and beauty" category was the most profitable, suggesting a popular and high-margin segment.

4. 🌟 Average Ratings by Product Line
Chart: Horizontal bar chart

Insight:
Electronic accessories received the highest average customer rating, implying strong satisfaction.

5. 🗓️ Sales by Day of the Week
Chart: Line plot of sales trends over days

Insight:
Friday showed the highest sales volume, useful for planning promotions or staffing.

🧾 Conclusion
From this analysis, we observed:

Branch C leads in performance, while Branch A may require marketing support.

Loyalty members are more valuable customers on average.

Health & Beauty and Electronic Accessories are key categories driving revenue and satisfaction.

Customer ratings provide valuable feedback for product line optimisation.

Recommendations:

Boost promotions at Branch A

Expand high-performing product lines

Target loyalty programs to increase membership
