# 🛒 Retail Sales Exploratory Data Analysis (EDA)

## 📌 Project Overview

Retail businesses generate a large amount of transaction data every day. Analyzing this data helps organizations understand customer purchasing behavior, identify sales trends, evaluate product performance, and make informed business decisions.

This project performs a comprehensive Exploratory Data Analysis (EDA) on a retail sales dataset using Python. The project covers data loading, data cleaning, descriptive statistics, visualization, trend analysis, and business recommendations.

The goal is to transform raw sales data into meaningful insights that support better decision-making.

---

# 🎯 Project Objectives

The primary objectives of this project are:

- Understand the structure of the retail sales dataset.
- Identify missing values and duplicate records.
- Clean and preprocess the data.
- Calculate descriptive statistics.
- Analyze customer demographics.
- Study monthly and quarterly sales trends.
- Analyze product category performance.
- Understand relationships between numerical variables.
- Generate business insights.
- Recommend data-driven business strategies.

---

# 📂 Dataset Description

The dataset contains **1000 retail transactions**.

## Dataset Columns

| Column Name | Description |
|-------------|-------------|
| Transaction ID | Unique transaction identifier |
| Date | Purchase date |
| Customer ID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Product Category | Category of purchased product |
| Quantity | Number of products purchased |
| Price per Unit | Price of one product |
| Total Amount | Total bill amount |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📊 Python Libraries

### Pandas
Used for:
- Data loading
- Data cleaning
- Data manipulation
- Aggregation
- Grouping

### NumPy
Used for:
- Numerical operations
- Statistical calculations

### Matplotlib
Used for:
- Line charts
- Bar charts
- Scatter plots
- Histograms

### Seaborn
Used for:
- Heatmaps
- Boxplots
- Pairplots
- Statistical visualizations

---

# 📋 Project Workflow

## Step 1 — Import Libraries

Imported all required Python libraries.

---

## Step 2 — Load Dataset

Loaded the CSV dataset using Pandas.

---

## Step 3 — Initial Data Inspection

Performed:

- Dataset shape
- Column names
- Data types
- First five records
- Last five records

---

## Step 4 — Data Cleaning

Performed:

- Duplicate check
- Duplicate removal
- Missing value check
- Date conversion
- Created Month column
- Created Quarter column

---

## Step 5 — Descriptive Statistics

Calculated:

- Mean
- Median
- Mode
- Standard deviation
- Minimum value
- Maximum value
- Quartiles

---

## Step 6 — Exploratory Data Analysis

The following analyses were performed.

### Monthly Sales Trend

Purpose:
- Understand monthly sales variation.

Observation:
- Sales fluctuate across different months.
- Some months generate significantly higher revenue.

---

### Quarterly Sales Trend

Purpose:
- Compare quarterly performance.

Observation:
- Certain quarters outperform others.
- Seasonal demand influences quarterly revenue.

---

### Gender Distribution

Purpose:
- Analyze customer demographics.

Observation:
- Both male and female customers contribute significantly to sales.

---

### Age Distribution

Purpose:
- Understand customer age groups.

Observation:
- Most customers belong to the adult age category.

---

### Revenue by Product Category

Purpose:
- Identify best-performing categories.

Observation:
- Clothing and Electronics generate higher revenue than other categories.

---

### Quantity Sold by Category

Purpose:
- Compare demand across product categories.

Observation:
- Some categories have consistently higher purchase quantities.

---

### Correlation Heatmap

Purpose:
- Measure relationships between numerical variables.

Observation:
- Quantity and Price per Unit strongly influence Total Amount.
- Age has a weak correlation with sales.

---

### Sales Distribution

Purpose:
- Understand purchase amount distribution.

Observation:
- Most purchases fall within a moderate spending range.
- A few high-value transactions exist.

---

### Price Distribution

Purpose:
- Analyze pricing patterns.

Observation:
- Most products have moderate prices.
- Premium-priced products contribute to higher revenue.

---

### Scatter Plot

Purpose:
- Compare Age vs Total Amount.

Observation:
- No strong relationship exists between customer age and purchase amount.

---

### Pair Plot

Purpose:
- Explore relationships among numerical variables.

Observation:
- Quantity positively affects Total Amount.

---

### Box Plot

Purpose:
- Detect outliers.

Observation:
- High-value purchases appear as outliers.

---

### Top Customers

Purpose:
- Identify highest spending customers.

Observation:
- A small number of customers contribute significantly to total revenue.

---

# 📈 Business Insights

- Clothing and Electronics are the highest revenue-generating categories.
- Customer purchasing behavior changes throughout the year.
- Product quantity has a direct impact on total sales.
- Price per Unit significantly influences revenue.
- High-value customers contribute a large share of total income.
- Seasonal trends affect business performance.
- Most customers make medium-value purchases.
- Sales data provides opportunities for targeted marketing.

---

# 💡 Business Recommendations

1. Increase inventory for high-demand product categories.

2. Introduce seasonal promotional campaigns.

3. Reward loyal customers through loyalty programs.

4. Offer discounts for low-performing categories.

5. Use customer demographics for personalized marketing.

6. Focus advertising during peak sales months.

7. Improve pricing strategies using historical sales analysis.

8. Monitor top customers and provide exclusive offers.

9. Expand high-performing product categories.

10. Continuously monitor sales trends for forecasting.

---

# 📌 Project Outcomes

After completing this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- Business Insight Generation
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 🚀 Future Scope

This project can be extended by:

- Building an interactive Power BI dashboard.
- Creating a Tableau dashboard.
- Developing a Sales Forecasting model using Machine Learning.
- Performing Customer Segmentation using K-Means clustering.
- Predicting customer lifetime value.
- Building a recommendation system.

---

# 📁 Project Structure

```
Retail_Sales_EDA/
│
├── retail_sales_dataset.csv
├── Retail_Sales_EDA.ipynb
├── README.md
├── Report.pdf
├── Images/
│
└── requirements.txt
```

---

# 📜 Conclusion

The Retail Sales EDA project demonstrates how raw business data can be transformed into meaningful insights through data cleaning, statistical analysis, and visualization. The findings help identify customer purchasing behavior, sales trends, and product performance, enabling organizations to make informed business decisions.

This project showcases practical skills in Python, data analysis, and business intelligence, making it a strong addition to a Data Analyst portfolio.

---

# 👨‍💻 Author

**Y. N. Charan Reddy**

**Data Analyst Aspirant**

### Skills Demonstrated

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Business Analytics
