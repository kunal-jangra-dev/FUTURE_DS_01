# Sales Performance Analysis (Python + Power BI)

## Project Overview
This project focuses on analyzing retail sales data to understand sales trends, product performance, and regional performance.

It was done as part of an internship project by Future Intern, with the aim of applying data analysis concepts to a real-world type dataset.

---

## Tools Used
- Python (Pandas, NumPy, Matplotlib)
- Power BI

---

## Dataset
I used the Sample Superstore dataset which contains order-level data such as sales, profit, region, and product categories.

---

## Data Preparation
- Converted Order Date and Ship Date into datetime format
- Extracted Year, Month, and Month Name from Order Date
- Checked for missing values and duplicates

---

## Analysis

### Monthly Sales Trend
- Sales follow a seasonal pattern
- Highest sales are in November and December
- Early months like February have lower sales

### Product Performance
- Phones and Chairs generate the most sales
- Some categories like Tables have high sales but negative profit

### Profit Analysis
- Copiers and Phones are the most profitable
- Some products are loss-making due to pricing or discounts

### Regional Analysis
- West region performs the best in both sales and profit
- Central region has lower profit compared to its sales

---

## Power BI Dashboard
I created an interactive dashboard in Power BI to visualize:
- Monthly sales trend
- Sales by region
- Profit by category
- Top products

Features:
- KPI cards (Total Sales, Total Profit, Profit Margin)
- Slicers for filtering data

![Dashboard](dashboard.png)

---

## Key Insights
- Sales increase significantly in Q4
- High sales do not always mean high profit
- Some regions and products need better cost management

---

## Conclusion
This project helped me understand how data analysis can be used to find useful business insights and support decision-making.

---

## Project Structure
FUTURE_DS_01/
│
├── Project_1_Sales_Analysis/
│   ├── Superstore.ipynb
│   ├── Sample - Superstore.csv
│   ├── Superstore.pbix
│   └── README.md
