# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to identify spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

---

## 📊 Dataset Summary
- **Total Records:** 3,900  
- **Total Columns:** 18  

### Key Features
- Customer Demographics: Age, Gender, Location, Subscription Status  
- Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color  
- Shopping Behavior: Discount Applied, Previous Purchases, Review Rating, Shipping Type  
- Missing Data: 37 values in the Review Rating column  

---

## 🛠️ Tools & Technologies
- Python (pandas, numpy)
- PostgreSQL
- SQL
- Power BI
- Excel

---

## 🧹 Data Cleaning & Preparation (Python)
- Loaded and explored data using pandas  
- Handled missing values using median imputation by category  
- Standardized column names using snake_case  
- Feature engineering:
  - Created age_group column  
  - Created purchase_frequency_days feature  
- Removed redundant columns after consistency checks  
- Loaded cleaned data into PostgreSQL for analysis  

---

## 🧮 SQL Analysis (Business Questions)
- Revenue by gender  
- High-spending customers who used discounts  
- Top 5 products by average review rating  
- Average purchase amount by shipping type  
- Subscriber vs non-subscriber spending behavior  
- Products most dependent on discounts  
- Customer segmentation (New, Returning, Loyal)  
- Top 3 products per category  
- Repeat buyers and subscription relationship  
- Revenue contribution by age group  

---
## 📊 Power BI Dashboard
An interactive Power BI dashboard was built to visualize insights and trends.

🔗 **Live Dashboard:** [View Interactive Power BI Report](https://app.powerbi.com/groups/me/reports/5b28c9ec-f10b-475d-ad9d-6cc4d9f65b29/c5493eb082fcc0658904?experience=power-bi)

### Dashboard Highlights
- Total customers: 3.9K  
- Average purchase amount: $59.76  
- Average review rating: 3.75  
- Revenue and sales by category  
- Revenue and sales by age group  
- Subscription-based customer insights  
- Interactive slicers for detailed exploration  

---

## 💡 Key Insights
- Male customers generated higher overall revenue  
- Express shipping users showed slightly higher average spend  
- Subscribers contributed significantly to repeat purchases  
- Certain products are highly discount-driven  
- Young Adult and Middle-aged customers generated the highest revenue  
- Majority of customers belong to the Loyal segment  

---

## 📌 Business Recommendations
- Promote subscription plans to increase customer retention  
- Introduce loyalty programs for repeat buyers  
- Optimize discount strategies to protect profit margins  
- Highlight top-rated and best-selling products in campaigns  
- Focus targeted marketing on high-revenue age groups  

---

## 🚀 Conclusion
This project demonstrates an end-to-end data analytics workflow, including data cleaning in python , SQL-based analysis, and interactive dashboard creation. It highlights strong analytical, technical, and business insight skills using Python, SQL, and Power BI.
