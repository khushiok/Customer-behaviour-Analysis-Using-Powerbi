# 📊 Customer Shopping Behavior Analysis

**Python | SQL Server | Power BI**

An end-to-end data analytics project focused on understanding customer shopping behavior, purchasing patterns, product preferences, customer segments, discounts, subscriptions, and revenue trends.

## 📌 Overview

This project analyzes **3,900 purchase records across multiple product categories** to identify customer behavior patterns and generate actionable business insights. The workflow covers data preparation and exploratory analysis in Python, business analysis using SQL Server, and interactive visualization through Power BI.

The main objective is to understand how customer demographics, purchasing behavior, discounts, product categories, subscriptions, and other factors influence sales and customer engagement.

## 🎯 Business Objective

The project addresses the following business question:

> **How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?**

The analysis focuses on:

* Customer spending and revenue patterns
* Product and category performance
* Customer segmentation and loyalty
* Discount usage and purchasing behavior
* Subscription behavior
* Shipping preferences
* Revenue contribution across age groups

## 📂 Dataset

The dataset contains **3,900 records and 18 columns** covering:

* **Customer Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
* **Shopping Behavior:** Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

The dataset initially contained **37 missing values in the Review Rating column**.

## 🛠️ Tools & Technologies

| Tool                   | Purpose                                           |
| ---------------------- | ------------------------------------------------- |
| **Python**             | Data loading, cleaning, EDA & feature engineering |
| **Pandas**             | Data manipulation and analysis                    |
| **SQL Server / T-SQL** | Business analysis and querying                    |
| **Power BI**           | Interactive dashboard and data visualization      |
| **GitHub**             | Version control and project documentation         |

## 🔄 Project Workflow

### 1. Data Loading & Exploratory Data Analysis — Python

The dataset was loaded using **Pandas** and explored using functions such as `info()` and `describe()` to understand its structure and statistical characteristics.

### 2. Data Cleaning & Transformation

The following preprocessing steps were performed:

* Checked and handled missing values
* Imputed missing review ratings using the median rating of each product category
* Standardized column names using snake_case
* Created an `age_group` feature
* Created `purchase_frequency_days`
* Checked for redundant columns and removed `promo_code_used`
* Prepared the cleaned dataset for SQL analysis

### 3. SQL Server Analysis

The cleaned dataset was analyzed using **SQL Server and T-SQL** to answer business-focused questions, including:

* Revenue by gender
* High-spending customers using discounts
* Top-rated products
* Average spending by shipping type
* Subscribers vs. non-subscribers
* Products with the highest discount rates
* Customer segmentation
* Top products within each category
* Repeat buyers and subscription behavior
* Revenue by age group

### 4. Power BI Dashboard

An interactive **Power BI dashboard** was developed to present the analysis visually and allow users to explore customer behavior through different filters and KPIs.

## 📊 Dashboard

The dashboard provides an overview of:

* Total customers/purchases
* Average purchase amount
* Average review rating
* Subscription status
* Revenue by category
* Sales by category
* Revenue by age group
* Sales by age group
* Interactive filters for customer and shopping attributes

## 🔍 Key Results & Insights

Some of the major findings from the analysis include:

* **Clothing** generated the highest revenue and sales among the major product categories.
* **Young Adults** contributed the highest total revenue among the analyzed age groups.
* **Express shipping** customers had a higher average purchase amount than Standard shipping customers.
* A large majority of records belonged to the **non-subscriber segment**, highlighting an opportunity to improve subscription conversion.
* The **Loyal** customer segment represented the largest customer group based on purchase history.
* **Hats, Sneakers, Coats, Sweaters, and Pants** showed the highest percentages of discounted purchases.
* **Gloves, Sandals, Boots, Hats, and Skirts** ranked among the highest-rated products.

## 💡 Business Recommendations

Based on the analysis:

1. **Boost Subscriptions**
   Promote exclusive benefits and incentives to increase subscription adoption.

2. **Strengthen Customer Loyalty**
   Reward repeat buyers and encourage customers to move into the Loyal segment.

3. **Review Discount Strategy**
   Evaluate discount-heavy products to balance sales growth with profitability.

4. **Improve Product Positioning**
   Highlight highly rated and best-selling products in marketing campaigns.

5. **Use Targeted Marketing**
   Focus campaigns on high-revenue age groups and customers showing stronger purchase engagement.

## 📁 Project Structure

```text
Customer-behaviour-Analysis-Using-PowerBI/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behaviour_sqlserver_queries.sql
├── customer_behaviour_dashboard_2026.pbix
├── Business Problem Document.pdf
├── Customer Shopping Behavior Analysis.pdf
├── LICENSE
└── README.md
```

## 🚀 How to Run

### Step 1 — Python Analysis

Open:

```text
Customer_Shopping_Behavior_Analysis.ipynb
```

Run the notebook to:

* Load the dataset
* Explore the data
* Clean missing values
* Perform feature engineering
* Prepare the dataset for SQL analysis

### Step 2 — SQL Server

1. Create a database in SQL Server.
2. Import the cleaned dataset.
3. Open:

```text
customer_behaviour_sqlserver_queries.sql
```

4. Run the T-SQL queries to reproduce the business analysis.

### Step 3 — Power BI

1. Open:

```text
customer_behaviour_dashboard_2026.pbix
```

2. Connect Power BI to the SQL Server database.
3. Refresh the dataset if required.
4. Explore the interactive dashboard.

## 📚 Project Reference & Acknowledgement

This project was **inspired by and adapted from the customer shopping behavior analytics project by Amlan Mohanty**. The original project served as a reference for the overall analytics workflow, project structure, and dashboard/analysis approach. The implementation in this repository has been adapted and worked through using **SQL Server/T-SQL and Power BI**, along with my own analysis, documentation, and project presentation.

Credit and appreciation to **Amlan Mohanty** for making the original project available as a learning reference.

## 👤 Author

**Khushi Shah**

Data Analytics | Python | SQL | Power BI

---

*This project was created as a learning and portfolio project to demonstrate an end-to-end data analytics workflow.*

