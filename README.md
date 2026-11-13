# 🛍️ Customer Shopping Behavior Analysis

An end-to-end data analytics project exploring customer purchasing patterns, spending behavior, product preferences, and customer segmentation using Python, PostgreSQL, SQL, and Power BI.

## 📌 Project Overview

This project analyzes customer shopping behavior using a dataset containing 3,900 transactions and 18 attributes. The objective is to identify meaningful patterns in customer purchases, understand spending habits, evaluate product preferences, and generate actionable business insights.

The project follows a complete data analytics workflow, starting with data cleaning and preprocessing in Python, followed by database integration and SQL-based business analysis, and finally presenting insights through an interactive Power BI dashboard.

## 🛠️ Technologies & Tools Used

- **Python:** Data analysis and preprocessing.
- **Pandas & NumPy:** Data manipulation, cleaning, and transformation.
- **Matplotlib & Seaborn:** Data visualization.
- **Jupyter Notebook:** Python development and analysis.
- **PostgreSQL:** Database management and data storage.
- **SQL:** Business queries and analytical insights.
- **Power BI:** Interactive dashboard and data visualization.

## 📂 Repository Contents

This repository includes the following project files:

### 1. Dataset – `customer_shopping_behavior.csv`

The original dataset containing 3,900 customer transactions and 18 attributes.

It includes:
- Customer demographics (Age, Gender, Location).
- Purchase details (Item Purchased, Category, Purchase Amount).
- Product information (Size, Color, Season).
- Shopping behavior (Discount Applied, Promo Code Used).
- Customer information (Subscription Status, Previous Purchases).
- Purchase frequency, review ratings, and shipping details.

### 2. Jupyter Notebook – `Customer_bevaiour_analysis.ipynb`

Contains the complete Python-based data preparation and preprocessing workflow.

Key activities:
- Loading the dataset using Pandas.
- Exploring the dataset using `info()` and `describe()`.
- Identifying and handling missing values.
- Imputing missing review ratings using category-wise median values.
- Standardizing column names using snake_case.
- Creating an `age_group` feature using quantile-based binning.
- Creating a `purchase_frequency_days` feature.
- Checking redundant columns and removing unnecessary attributes.
- Connecting the cleaned DataFrame to PostgreSQL using SQLAlchemy.

### 3. SQL Analysis – `customer_shopping_analysis.sql`

Contains the SQL queries written and executed in PostgreSQL to answer 10 business questions.

The analysis includes:

1. Revenue by Gender.
2. High-Spending Discount Users.
3. Top 5 Products by Rating.
4. Shipping Type Comparison.
5. Subscribers vs. Non-Subscribers.
6. Discount-Dependent Products.
7. Customer Segmentation.
8. Top 3 Products per Category.
9. Repeat Buyers & Subscriptions.
10. Revenue by Age Group.

These queries help identify customer purchasing patterns, revenue trends, product preferences, and subscription behavior.

### 4. Power BI Dashboard – `customer_behavior_dashboard1.pbix`

An interactive Power BI dashboard developed to visualize customer shopping behavior and present key performance indicators.

Dashboard components:
- Total Number of Customers.
- Average Purchase Amount.
- Average Review Rating.
- Customer Distribution by Subscription Status.
- Revenue by Category.
- Sales by Category.
- Revenue by Age Group.
- Sales by Age Group.

Interactive filters are available for subscription status, gender, category, and shipping type.

### 5. Project Documentation – `Customer Shopping Behavior Analysis.pdf`

Provides detailed documentation of the project, including:

- Project overview and dataset summary.
- Data cleaning and preprocessing steps.
- Feature engineering.
- PostgreSQL database integration.
- SQL business questions and query results.
- Power BI dashboard.
- Business recommendations.

### 6. Project Presentation – `Customer_Shopping_Behavior_Analysis.pptx`

A presentation summarizing the project and its major findings.

It covers:
- Project introduction and analytical approach.
- Revenue analysis by gender and age group.
- Subscription and customer segmentation insights.
- Product ratings and discount dependency.
- Power BI dashboard.
- Business recommendations.

## 📊 Key Business Insights

- **Revenue by Gender:** Male customers contributed higher total revenue, while spending per customer was relatively similar.
- **Customer Segmentation:** Loyal customers represented approximately 80% of the customer base.
- **Subscription Analysis:** Approximately 27% of customers had subscriptions.
- **Product Ratings:** Gloves received the highest average review rating.
- **Discount Analysis:** Hats had the highest discount dependency among the analyzed products.
- **Age Group Analysis:** Young Adults contributed the highest total revenue among the four age groups.
- **Shipping Analysis:** Express shipping customers had a slightly higher average purchase amount than Standard shipping customers.

## 💡 Business Recommendations

1. **Boost Subscriptions:** Promote exclusive benefits to encourage more customers to subscribe.
2. **Customer Loyalty Programs:** Reward repeat customers and strengthen customer retention.
3. **Review Discount Policies:** Balance discount-driven sales growth with profitability.
4. **Product Positioning:** Highlight top-rated and best-selling products in marketing campaigns.
5. **Targeted Marketing:** Focus marketing efforts on high-revenue customer segments.

## ⚙️ Project Workflow

1. Data Loading and Exploration – Python and Pandas.
2. Data Cleaning and Preprocessing – Handling missing values and standardizing columns.
3. Feature Engineering – Creating age groups and purchase frequency features.
4. Database Integration – Loading the cleaned dataset into PostgreSQL.
5. SQL Analysis – Answering 10 business questions using PostgreSQL.
6. Dashboard Development – Building an interactive Power BI dashboard.
7. Insights and Recommendations – Translating analytical findings into business recommendations.

## 🚀 Project Outcome

This project demonstrates the practical application of Python, data preprocessing, SQL, PostgreSQL, and Power BI in solving real-world business analytics problems.

It provides insights into customer behavior, purchasing patterns, product preferences, and revenue trends to support data-driven business decisions.

---

**Thank you for visiting this project!**
