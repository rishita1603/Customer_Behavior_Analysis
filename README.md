# 📊 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using retail transactional data to identify spending patterns, customer segments, product performance, and subscription trends. The project was completed as a **guided learning project**, with independent implementation of data cleaning, analysis, and visualization to strengthen practical data analytics skills.

The analysis follows an end-to-end workflow: **data preprocessing in Python → SQL-based business analysis → interactive visualization in Power BI**, resulting in actionable business insights.

## 🎯 Objectives

* Understand customer purchasing behavior and spending trends
* Identify high-value customers and loyal segments
* Analyze the impact of discounts and subscriptions on revenue
* Evaluate product performance using ratings and purchase frequency
* Present insights through an interactive dashboard


## 📂 Dataset Description

* **Total Records:** 3,900
* **Total Features:** 18
* **Key Attributes:**

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
  * Behavioral data (Discount Applied, Previous Purchases, Frequency of Purchases)
  * Service attributes (Shipping Type, Review Rating)
    
* **Missing Values:**

  * 37 missing values in the *Review Rating* column


## 🛠️ Tools & Technologies

* **Python:** Pandas, NumPy
* **Database:** PostgreSQL
* **Visualization:** Power BI
* **Version Control:** Git & GitHub


## 🔍 Data Cleaning & Preparation (Python)

* Loaded and explored data using pandas
* Inspected schema and summary statistics
* Handled missing review ratings using **category-wise median imputation**
* Standardized column names using snake_case
* Engineered new features:

  * `age_group` for demographic analysis
  * `purchase_frequency_days` to measure customer activity
* Identified and removed redundant columns
* Loaded cleaned data into PostgreSQL for SQL analysis

## 🧠 SQL Analysis (MySQL)

Business-focused queries were written to answer the following:

* Revenue distribution by **gender** and **age group**
* Spending behavior of **discount users**
* Comparison of **subscriber vs non-subscriber** revenue
* Top-rated products based on average review score
* Impact of **shipping type** on purchase amount
* Customer segmentation into:

  * New Customers
  * Returning Customers
  * Loyal Customers
* Identification of discount-dependent products
* Relationship between repeat purchases and subscription status


## 📊 Power BI Dashboard

An interactive dashboard was created to visualize:

* Revenue trends and customer segments
* Product performance across categories
* Subscription and discount behavior
* Demographic-based revenue contribution

The dashboard enables dynamic filtering for better business decision-making.

## 💡 Key Insights

* Loyal and repeat customers generate a significant share of revenue
* Subscribers tend to have higher average purchase values
* Some products rely heavily on discounts to drive sales
* High-rated products present strong opportunities for targeted promotions
* Certain age groups contribute disproportionately to overall revenue

## 📈 Business Recommendations

* Strengthen subscription programs with exclusive benefits
* Introduce loyalty rewards for repeat customers
* Optimize discount strategies to protect profit margins
* Promote top-rated and best-selling products
* Focus marketing efforts on high-revenue customer segments


**## Snapshots**

![Customer_Behavior_Analysis](Screenshots\Customer_Analysis.png)
![Customer_Behavior_Analysis](Screenshots\Customer_Analysis_2.png)
![Customer_Behavior_Analysis](Screenshots\Customer_Analysis_3.png)
