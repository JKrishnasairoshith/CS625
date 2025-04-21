
# Smart Spending at Walmart

**Author:** Krishna Sai Roshith (UIN:01299920)  
**Course:** CS625 – Data Visualization  
**Date:** April 20, 2025  

---

## 📊 Dataset Description

- **Source:** [Kaggle – Walmart Customer Purchase Behavior Dataset](https://www.kaggle.com/datasets/logiccraftbyhimanshi/walmart-customer-purchase-behavior-dataset)  
- **Size:** 50,000+ transactions  
- **Fields Used:** Customer ID, Gender, Age, City, Payment Method, Repeat Customer, Discount Applied, Rating, Purchase Date, Purchase Amount  
- **Preprocessing:** Created `Value_Score` (Spend ÷ Rating), extracted time features, and mapped city to state for location-based insights.

---

## ❓ Questions Addressed

### 1. Who are Walmart’s highest-value customers—and where are they located?
We defined a **value score** to identify customers who not only spend more but also rate their experience highly. Demographic and behavioral breakdowns (gender, age, payment method, discount use, and repeat status) were analyzed.

Geographically, we used a choropleth map to highlight where high-value customers are located, identifying **California** and **Texas** as the most valuable states.

### 2. When do Walmart customers spend the most?
Using weekly and hourly time features, we plotted a **line chart** showing repeat vs. new customer spend trends, and a **heatmap** showing average spend by hour of day and day of week.

The findings revealed that **weekends**, especially between **10 AM and 3 PM**, were peak periods for purchases.

---

## 📈 Final Visualizations

### 1. Dropdown Bar Chart: Avg Spend & Value Score by Segment  
*(Insert screenshot or image here)*

### 2. Choropleth Map: Avg Value Score by State  
*(Insert screenshot or image here)*

### 3. Weekly Spend Trend: Repeat vs New Customers  
*(Insert screenshot or image here)*

### 4. (Optional) Heatmap: Avg Spend by Hour & Day  
*(Insert screenshot or image here)*

---

## 📊 Idiom / Mark / Data / Encode Table

| Chart                     | Data Attribute     | Type          | Encoding                    |
|--------------------------|--------------------|---------------|-----------------------------|
| Bar Chart (Segment)      | Segment             | Categorical   | X-axis                      |
|                          | Avg Spend / Value   | Quantitative  | Y-axis (bar height), color  |
| Choropleth Map           | State               | Categorical   | Geo region, color scale     |
|                          | Value Score         | Quantitative  | Color intensity             |
| Line Chart (Spend Trend) | Week                | Temporal      | X-axis                      |
|                          | Spend               | Quantitative  | Y-axis (line height)        |
|                          | Customer Type       | Categorical   | Line color/group            |
| Heatmap (Hour/Day)       | Hour, DayOfWeek     | Categorical   | X & Y-axis, color intensity |

---

## 📌 Insights & Headline Summary

- **Repeat customers aged 26–35** offer the highest value and satisfaction, especially when not using discounts.
- **California and Texas** showed the strongest geographic concentration of high-value shoppers.
- **Weekends, particularly late mornings (10 AM – 3 PM)**, are optimal for marketing and operations.

These insights can guide loyalty programs, staffing, and regional campaigns.

---

## 🧠 Final Thoughts

- Time spent: ~20 hours  
- Most time-consuming: Data cleaning and interactivity setup  
- Most rewarding: Seeing stakeholder-ready insights emerge from real data  
- Future idea: Building a full dashboard with dropdowns, filters, and state-level drilldowns

---

## 🔗 References

- [Dataset on Kaggle](https://www.kaggle.com/datasets/logiccraftbyhimanshi/walmart-customer-purchase-behavior-dataset)  
- [Plotly Express Docs](https://plotly.com/python/plotly-express/)  
- [Pandas Documentation](https://pandas.pydata.org/docs/)  
- CS625 Assignment Brief and Guidelines

---
