# OIBSIP-DataAnalytics-L1-EDARetailSales-
#  Retail Sales Data Analysis

A comprehensive Exploratory Data Analysis (EDA) project on retail sales data using Python, Pandas, NumPy, Matplotlib, Seaborn, and Plotly. The project analyzes customer demographics, purchasing behavior, product performance, and sales trends to generate actionable business insights and recommendations.

---

##  Table of Contents

* [Overview](#overview)
* [Business Problem](#business-problem)
* [Dataset](#dataset)
* [Tools & Technologies](#tools--technologies)
* [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Research Questions & Findings](#research-questions--findings)
* [How to Run](#how-to-run)
* [Business Recommendations](#business-recommendations)

---

##  Overview

This project explores retail sales data to understand customer behavior, sales performance, and revenue patterns. Through data visualization and statistical analysis, the project identifies trends that can help businesses make informed decisions regarding marketing, inventory management, and customer targeting.

---

##  Business Problem

Retail businesses generate large amounts of transactional data, but transforming this data into actionable insights can be challenging.

This project aims to answer key business questions such as:

* Which customer groups contribute the most revenue?
* How do sales vary across months and quarters?
* Which product categories perform best?
* Are there noticeable spending patterns based on age and gender?
* What strategies can improve revenue and customer engagement?

---

##  Dataset

- **Rows (Records):** 1000
- **Columns (Features):** 9
- **Dataset Shape:** 1000 × 9

The dataset contains retail transaction records including:

| Feature          | Description                   |
| ---------------- | ----------------------------- |
| Transaction ID   | Unique transaction identifier |
| Date             | Transaction date              |
| Customer ID      | Customer identifier           |
| Gender           | Male/Female                   |
| Age              | Customer age                  |
| Product Category | Product purchased             |
| Quantity         | Quantity purchased            |
| Price per Unit   | Unit price                    |
| Total Amount     | Total transaction value       |

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

##  Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Checked for missing values
* Checked for duplicate records
* Converted date column to datetime format
* Extracted month and quarter information
* Verified data types
* Generated descriptive statistics
* Organized month names in chronological order for time-series analysis

---

##  Exploratory Data Analysis

The following analyses were conducted:

### Customer Demographics

* Gender distribution
* Age distribution
* Revenue by age group
* Revenue by gender and age group

### Sales Analysis

* Monthly sales trend
* Quarterly sales trend
* Revenue analysis

### Product Analysis

* Product category distribution
* Revenue by product category
* Category-wise sales performance

### Statistical Analysis

* Summary statistics
* Distribution plots
* Outlier detection using boxplots
* Correlation analysis

---

## Research Questions & Findings

### 1. Which age group contributes the most revenue?
Slightly higher customer concentrations are visible around the 40–55 age(middle-aged) range.
Middle-aged customers were found to contribute significantly to overall revenue, making them a valuable customer segment.

### 2. How does revenue change over time?

Sales fluctuate throughout the year, with certain months and quarters outperforming others, indicating seasonal purchasing behavior.
May was the best-performing month, while September experienced the lowest revenue, indicating clear seasonality in sales performance.Q4 was the highest-revenue quarter, while Q3 was the weakest. 

### 3. Which product category generated most revenue?

Beauty products generated highest revenue followed by electronics and clothing.

### 4. Which product category sold the most unit?

Clothing sold the most unit followed by electronics then beauty.

### 5. How does revenue vary across different age groups and genders?

Revenue contribution varies across age groups and genders. Certain age segments generate higher revenue than others, indicating differences in purchasing behavior. Both male and female customers contribute significantly to overall sales, with some age-gender combinations showing stronger revenue performance.

### 6. Is there a difference in spending behavior by gender?

Revenue contribution from male and female customers was relatively balanced, suggesting both customer segments are equally important.

### 7. Are there outliers in the dataset?

Boxplot analysis indicated no significant outliers in age, while transaction amounts showed a right-skewed distribution due to some high-value purchases.

---

##  How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Retail-Sales-EDA.git
```

2. Load the CSV file
   
3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run the notebook

```bash
Retail_Sales_Analysis.ipynb
```

---

## 💡 Business Recommendations

### 1. Focus on High-Value Customer Segments

Target the highest-spending age groups with personalized marketing campaigns and loyalty programs.

### 2. Improve Low-Performing Periods

Introduce promotions and discounts during months and quarters with lower sales performance.

### 3. Optimize Inventory Planning

Increase inventory levels before peak sales periods to avoid stock shortages.

### 4. Strengthen Product Category Strategy

Invest more resources in top-performing product categories while improving visibility of lower-performing categories.

### 5. Use Data-Driven Marketing

Leverage customer demographic insights to design more targeted and effective marketing campaigns.

---

##  Author

**Sayam Stuti Shuvadarsini**

B.Tech CSE (Data Science) | ITER, SOA University

Aspiring Data Analyst & Data Scientist
 Email: sayamstuti594@gmail.com

 LinkedIn: www.linkedin.com/in/sayam-stuti-shuvadarsini-8089b43a4

