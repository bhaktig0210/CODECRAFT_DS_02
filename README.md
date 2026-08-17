# CODECRAFT_DS_02
CODCRAFT Data Science Internship Projects


# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project focuses on **Data Cleaning and Exploratory Data Analysis (EDA)** of customer shopping behavior using Python.

The objective is to analyze customer demographics, purchasing patterns, product categories, payment preferences, purchase channels, customer segments, and revenue trends to identify meaningful patterns and generate actionable business insights.

---

## 🎯 Objectives

- Understand the structure and characteristics of the dataset
- Clean and preprocess the data
- Identify and handle missing values
- Detect and remove duplicate records
- Analyze customer demographics
- Explore purchasing behavior and spending patterns
- Compare purchase amounts across different categories and segments
- Analyze revenue by category, city, and customer segment
- Study relationships between numerical variables
- Detect potential outliers
- Generate meaningful business insights

---

## 📊 Dataset Information

The dataset contains customer shopping and transaction information.

### Dataset Details

- **Initial Records:** 1,005
- **Final Records:** 1,000
- **Columns:** 10
- **Duplicate Records Removed:** 5
- **Missing Values After Cleaning:** 0

### Features

| Column | Description |
|---|---|
| `Customer_ID` | Unique customer identifier |
| `Age` | Age of the customer |
| `Gender` | Gender of the customer |
| `City` | Customer's city |
| `Category` | Product category purchased |
| `Purchase_Amount` | Amount spent by the customer |
| `Payment_Method` | Payment method used |
| `Customer_Segment` | Customer segment |
| `Purchase_Channel` | Channel used for purchasing |
| `Customer_Rating` | Customer rating |

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🧹 Data Cleaning

The following data cleaning steps were performed:

1. Inspected the dataset structure and data types.
2. Checked for missing values.
3. Identified duplicate records.
4. Removed 5 duplicate records.
5. Handled missing numerical values using the median.
6. Handled missing categorical values using the mode.
7. Validated the cleaned dataset.
8. Confirmed that no missing values or duplicates remained.

### Final Dataset Status

| Metric | Result |
|---|---:|
| Records | 1,000 |
| Columns | 10 |
| Missing Values | 0 |
| Duplicate Records | 0 |

---

## 📈 Exploratory Data Analysis

### Univariate Analysis

The following variables were analyzed individually:

- Age Distribution
- Purchase Amount Distribution
- Customer Rating Distribution
- Gender Distribution
- City Distribution
- Product Category Distribution
- Payment Method Distribution
- Customer Segment Distribution
- Purchase Channel Distribution

### Bivariate Analysis

Relationships between variables were explored using:

- Age vs Purchase Amount
- Purchase Amount by Gender
- Purchase Amount by Category
- Purchase Amount by Customer Segment
- Purchase Amount by Payment Method
- Purchase Amount by Purchase Channel

### Revenue Analysis

Revenue was analyzed across:

- Product Categories
- Cities
- Customer Segments

### Statistical Analysis

- Correlation Analysis
- Outlier Detection
- Descriptive Statistics

---

## 🔍 Key Findings

### Customer Behavior

- **Online** is the most frequently used purchase channel.
- **Regular customers** represent the largest customer segment.
- Female customers are slightly more numerous than male customers.
- Customers are distributed across a broad age range.

### Product & Revenue Analysis

- **Beauty** has the highest number of purchases.
- **Home & Kitchen** generates the highest total revenue among product categories.
- Clothing generates comparatively lower total revenue.

### City Analysis

- **Nagpur** has the highest number of customers.
- Nagpur also generates the highest total revenue among the analyzed cities.
- Customer and revenue distribution varies across cities.

### Payment Analysis

- **Debit Card** is the most frequently used payment method.
- **UPI** has the highest average purchase amount.
- Credit Card has the lowest average purchase amount among the analyzed payment methods.

### Purchase Channel Analysis

- **Online** has the highest average purchase amount.
- Store purchases have the lowest average purchase amount.
- Online purchasing is an important channel for higher-value transactions.

### Correlation Analysis

- Age and Purchase Amount show a very weak relationship.
- Age and Customer Rating show almost no linear relationship.
- Purchase Amount and Customer Rating also show a very weak relationship.

### Outlier Analysis

- No significant extreme outliers were observed in Age, Purchase Amount, or Customer Rating based on the box plot analysis.

---

## 💡 Business Insights

The analysis suggests that:

- The business should continue focusing on its **online sales channel**.
- Regular customers are an important contributor to overall revenue and can be targeted through loyalty programs.
- Home & Kitchen represents a strong revenue-generating category.
- City-level analysis can help identify high-performing markets and opportunities for growth.
- Payment preferences can be considered when designing promotional campaigns.
- Customer age alone is not a strong indicator of purchase value, so multiple customer attributes should be considered for segmentation and targeting.

🧠 Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
Data Visualization
Statistical Analysis
Missing Value Handling
Duplicate Detection
Outlier Detection
Correlation Analysis
Business Intelligence
Business Insight Generation
Python
Pandas
NumPy
Matplotlib
Seaborn
👩‍💻 Author

Bhakti Ghogare

B.E. in Information Technology

Data Analyst | Python | SQL | Power BI | Excel

