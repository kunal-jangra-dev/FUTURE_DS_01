# Marketing Funnel & Conversion Analysis

## Project Overview
This project analyzes user behavior across an e-commerce conversion funnel using real-world event data from an online retail platform. The goal of the analysis is to identify user drop-off points, understand customer behavior patterns, and generate business recommendations to improve conversion performance.

The analysis focuses on three major funnel stages:

- View
- Cart
- Purchase

A Power BI dashboard and Python-based exploratory analysis were used to derive insights from the dataset.

---

## Objectives

- Analyze user movement through the e-commerce funnel
- Identify major drop-off stages
- Measure conversion performance
- Segment users based on conversion speed
- Generate business recommendations for optimization

---

## Dataset Information

Dataset: eCommerce Behavior Data from Multi-Category Store

- Source: Kaggle
- Time Period: October 2019
- Records Used: First 400,000 events
- Event Types Considered:
  - view
  - cart
  - purchase

### Features Used
- event_time
- event_type
- product_id
- category_id
- user_id

---

## Technologies Used

### Programming & Analysis
- Python
- Pandas
- NumPy
- Matplotlib

### Business Intelligence
- Power BI

---

## Data Preprocessing

The following preprocessing steps were performed:

- Selected relevant columns
- Filtered only funnel-related events
- Converted timestamps into datetime format
- Sorted events by user and time
- Removed duplicate user-event combinations
- Constructed user-level conversion funnel

---

## Funnel Methodology

The funnel was analyzed at the user level rather than event count level to avoid inflated metrics caused by repeated views or interactions.

### Funnel Flow
View → Cart → Purchase

### Key Metrics Calculated
- View-to-Cart Rate
- Cart-to-Purchase Rate
- Total Conversion Rate
- Funnel Drop-off Percentage
- User Conversion Speed Segments

---

## Key Insights

### Major View-to-Cart Drop-off
The highest drop-off occurs between the View and Cart stages, indicating that users browse products but often fail to take action.

### Strong Cart-to-Purchase Performance
Users who add items to the cart demonstrate relatively high purchase intent and are more likely to complete transactions.

### User Intent Segmentation
Users were segmented into:
- Fast Responders (<2 minutes)
- Medium Decision Makers (2–10 minutes)
- Slow Researchers (>10 minutes)

This helps understand purchasing behavior and decision-making patterns.

---

## Business Recommendations

- Improve product page quality with better images and descriptions
- Optimize “Add to Cart” visibility and UI design
- Use urgency triggers such as discounts or low-stock indicators
- Implement retargeting campaigns for non-converting users
- Introduce personalized product recommendations

---

## Dashboard Features

The Power BI dashboard includes:

- KPI Cards
  - Total Revenue
  - Total Purchases
  - Conversion Rate
  - Total Users

- Funnel Analysis
- Revenue by Brand
- Revenue by Category
- Event Distribution Charts
- User Behavior Insights

---

## Project Structure

├── dashboard.pbix
└── README.md
