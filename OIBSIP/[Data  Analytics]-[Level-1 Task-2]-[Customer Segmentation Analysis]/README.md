# Customer Segmentation Analysis using K-Means Clustering

## Oasis Infobyte Data Analytics Internship

### Task 2 - Customer Segmentation Analysis

---

## Project Overview

Customer segmentation is the process of dividing customers into different groups based on their purchasing behavior. This project applies **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering** to identify customer segments from an Online Retail dataset.

The identified customer groups help businesses understand customer behavior and create personalized marketing strategies to improve customer retention and increase revenue.

---

## Objective

The objective of this project is to:

- Analyze customer purchasing behavior.
- Perform RFM Analysis.
- Normalize customer features.
- Apply K-Means Clustering.
- Identify different customer segments.
- Recommend marketing strategies for each customer group.

---

## Dataset

**Dataset Name:** Online Retail Dataset

The dataset contains customer purchase transactions from an online retail store.

### Features

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Import dataset
- Display dataset information
- Understand data structure

### 2. Data Cleaning

- Check missing values
- Remove missing records
- Convert InvoiceDate to DateTime format
- Create TotalPrice feature

### 3. Feature Engineering

Created:

TotalPrice = Quantity × UnitPrice

Performed RFM Analysis:

- Recency
- Frequency
- Monetary

---

### 4. Feature Scaling

Used:

StandardScaler()

to normalize all features before clustering.

---

### 5. Elbow Method

The Elbow Method was used to determine the optimal number of clusters for K-Means.

---

### 6. K-Means Clustering

Applied K-Means algorithm to divide customers into different groups.

---

### 7. Data Visualization

Created visualizations including:

- Missing Value Heatmap
- Distribution of Recency
- Distribution of Frequency
- Distribution of Monetary
- Correlation Heatmap
- Elbow Method Graph
- Customer Segments (Recency vs Monetary)
- Customer Segments (Frequency vs Monetary)
- Customers per Cluster
- Cluster Profile

---

### 8. Cluster Profiling

Calculated average:

- Recency
- Frequency
- Monetary

for each customer cluster.

---

### 9. Marketing Recommendations

Generated business recommendations for every customer segment.

---

## Results

The project successfully grouped customers into different segments based on purchasing behavior.

The segmentation helps businesses:

- Identify loyal customers
- Find high-value customers
- Detect inactive customers
- Improve customer retention
- Increase marketing effectiveness

---

## Business Insights

### High Value Customers

- Highest spending customers
- Frequent purchases
- Low Recency

Recommendation:

- Loyalty rewards
- VIP membership
- Exclusive discounts

---

### Regular Customers

Recommendation:

- Product recommendations
- Cross-selling
- Upselling

---

### At-Risk Customers

Recommendation:

- Personalized offers
- Email campaigns
- Discount coupons

---

### Low Value Customers

Recommendation:

- Welcome offers
- Engagement campaigns
- Promotional discounts

---

## Conclusion

Customer Segmentation using RFM Analysis and K-Means Clustering provides valuable insights into customer purchasing behavior.

Businesses can use these insights to improve customer satisfaction, increase sales, and optimize marketing strategies through personalized campaigns.

---

## Folder Structure

```
Task-2-Customer-Segmentation/
│
├── Customer_Segmentation.ipynb
├── data.csv
├── Customer_Segments.csv
├── README.md
├── requirements.txt
├── Customer_Segmentation_Report.pdf
│
└── Images
    ├── Missing_Values.png
    ├── Recency_Distribution.png
    ├── Frequency_Distribution.png
    ├── Monetary_Distribution.png
    ├── Correlation_Heatmap.png
    ├── Elbow_Method.png
    ├── Customers_Per_Cluster.png
    ├── Cluster_Recency_Monetary.png
    ├── Cluster_Frequency_Monetary.png
    └── Cluster_Profile.png
```

---

## Requirements

Install the required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Author

**Y. N. Charan Reddy**

Data Analytics Intern

Oasis Infobyte

