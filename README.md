# CODECRAFT_DS_02
CODCRAFT Data Science Internship Projects

# Customer Shopping Behavior – Exploratory Data Analysis

## 📌 Project Overview

This project focuses on **Data Cleaning and Exploratory Data Analysis (EDA)** of a customer shopping dataset containing 1,005 records and 10 columns.

The objective of this project is to clean the dataset, explore customer purchasing behavior, identify patterns and relationships between variables, and generate meaningful business insights using Python.

The analysis was performed using **Jupyter Notebook** with Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure and characteristics of the dataset
- Identify and handle missing values
- Detect and remove duplicate records
- Perform data quality checks
- Analyze numerical and categorical variables
- Identify relationships between customer attributes and purchase behavior
- Detect potential outliers
- Visualize important patterns and trends
- Generate meaningful business insights from the data

---

## 📊 Dataset Information

The dataset contains customer shopping information with the following columns:

| Column | Description |
|---|---|
| Customer_ID | Unique identifier for each customer |
| Age | Age of the customer |
| Gender | Gender of the customer |
| City | Customer's city |
| Category | Product category purchased |
| Purchase_Amount | Amount spent by the customer |
| Payment_Method | Payment method used |
| Customer_Segment | Customer classification |
| Purchase_Channel | Channel used for purchasing |
| Customer_Rating | Rating given by the customer |

### Dataset Size

- Initial Records: **1,005**
- Columns: **10**
- Duplicate Records Removed: **5**
- Final Records: **1,000**
- Final Missing Values: **0**

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧹 Data Cleaning

The following data cleaning steps were performed:

### 1. Data Loading

The dataset was imported into a Pandas DataFrame.

### 2. Data Inspection

The dataset was examined using:

- `head()`
- `tail()`
- `shape`
- `info()`
- `describe()`
- `dtypes`

### 3. Missing Value Analysis

Missing values were identified using:

```python
df.isnull().sum()
