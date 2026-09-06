# 📊 Customer Shopping Behavior Analysis

## Overview

An end-to-end **Data Analytics project** analyzing **3,900 customer purchase records** to understand purchasing behavior, product performance, customer loyalty, subscription patterns, discount usage, and revenue contribution.

The project follows a complete analytics workflow:

**Python → Data Cleaning & EDA → PostgreSQL/SQL → Power BI → Business Insights**

---

## 🎯 Business Objective

The objective is to transform raw customer shopping data into actionable insights that can help businesses improve:

- Customer retention and loyalty
- Subscription adoption
- Product positioning
- Discount strategies
- Targeted marketing
- Revenue generation

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| Python | Data preparation & EDA |
| Pandas | Data manipulation |
| Matplotlib / Seaborn | Data visualization |
| PostgreSQL | Database & SQL analysis |
| SQL | Business analysis |
| SQLAlchemy / psycopg2 | Database integration |
| Power BI | Interactive dashboard |
| GitHub | Version control & documentation |

---

## 🔄 Project Workflow

### 1. Python – Data Preparation & EDA

- Loaded and explored the dataset using Pandas
- Checked data types, statistics, missing values and data consistency
- Handled missing Review Rating values using category-level median
- Standardized column names to `snake_case`
- Created `age_group` using age quantiles
- Converted purchase frequency into numerical days
- Removed redundant `promo_code_used` data
- Loaded the cleaned dataset into PostgreSQL

### 2. PostgreSQL – SQL Business Analysis

Used SQL to answer **10 business questions**, including:

- Revenue by gender
- High-spending discount users
- Top 5 products by average rating
- Standard vs. Express shipping spending
- Subscriber vs. non-subscriber performance
- Products with the highest discount rates
- New, Returning and Loyal customer segmentation
- Top 3 products within each category
- Repeat buyers and subscription behavior
- Revenue contribution by age group

### 3. Power BI – Dashboard

Built an interactive **Customer Behavior Dashboard** with:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue & Sales by Category
- Revenue & Sales by Age Group
- Subscription Status
- Interactive filters for Gender, Category, Subscription Status and Shipping Type

---

## 🔍 Key Insights

- **3,900** customer purchase records were analyzed.
- **Loyal customers** formed the largest customer segment with **3,116 customers**.
- **Young Adults** generated the highest revenue among age groups: **$62,143**.
- **Express shipping** had a higher average purchase amount (**$60.48**) than Standard shipping (**$58.46**).
- **Gloves** had the highest average product rating at **3.86**.
- **Hat** had the highest percentage of discounted purchases at **50%**.
- Male customers generated higher total revenue than female customers in the dataset.

---

## 💡 Business Recommendations

- **Increase subscriptions:** Promote exclusive benefits and incentives for subscribers.
- **Strengthen loyalty:** Reward repeat buyers through customer loyalty programs.
- **Optimize discounts:** Balance promotional discounts with profit margins.
- **Improve product positioning:** Highlight highly-rated and best-selling products.
- **Target marketing:** Focus campaigns on high-revenue customer segments and relevant shipping/customer groups.

---

## 📊 Dashboard Preview

The Power BI dashboard provides an interactive view of customer behavior, sales, revenue, product categories, age groups and subscription status.

> Add your Power BI dashboard screenshot here.

---

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── report/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
├── presentation/
│   └── customer_behavior_presentation.pdf
│
└── README.md

## 🎯 Skills Demonstrated

**Python • Pandas • EDA • Data Cleaning • Feature Engineering • SQL • PostgreSQL • SQLAlchemy • Customer Segmentation • Business Analysis • Power BI • Data Visualization**

---

## 👩‍💻 Author

**Pragya Singh**

*Aspiring Data Analyst | Python | SQL | PostgreSQL | Power BI*
