# Customer Segmentation Analysis using RFM and K-Means Clustering

## Project Overview

This project performs **customer segmentation analysis** using transaction data to identify different types of customers based on their purchasing behavior.

The analysis combines **RFM (Recency, Frequency, Monetary) analysis** with **K-Means clustering** to group customers into meaningful segments. These segments help businesses understand customer value, improve marketing strategies, and increase customer retention.

Customer segmentation is widely used in **e-commerce, fintech, and marketing analytics** to identify high-value customers and optimize targeted campaigns.

---

# Objectives

The main objectives of this project are:

- Analyze customer purchasing behavior
- Identify high-value and low-value customer groups
- Segment customers using machine learning
- Provide actionable business insights for marketing and retention strategies

---

# Dataset

The dataset contains transaction-level information for customers, including:

| Column | Description |
|------|-------------|
| InvoiceNo | Transaction ID |
| StockCode | Product identifier |
| Description | Product description |
| Quantity | Number of items purchased |
| InvoiceDate | Transaction date |
| UnitPrice | Price per item |
| CustomerID | Unique customer identifier |
| Country | Customer country |

The dataset represents **e-commerce retail transactions**.

---

# Tools and Technologies

The analysis was performed using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Project Workflow

The project follows a structured data analysis pipeline:

## 1 Data Cleaning

Initial preprocessing steps included:

- Removing missing values
- Filtering invalid transactions
- Converting data types
- Handling negative quantities (returns)

Clean data is essential for accurate segmentation analysis.

---

## 2 Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to understand:

- Transaction distribution
- Customer purchase frequency
- Revenue distribution
- Customer activity patterns

Visualizations were used to detect patterns and outliers.

---

## 3 RFM Analysis

RFM stands for:

| Metric | Meaning |
|------|------|
| Recency | How recently a customer made a purchase |
| Frequency | How often the customer purchases |
| Monetary | How much money the customer spends |

These metrics were calculated for each customer and used to measure customer value.

Customers with:

- **Low Recency**
- **High Frequency**
- **High Monetary value**

are considered **high-value customers**.

---

## 4 Customer Segmentation using K-Means Clustering

Machine learning was used to segment customers.

Steps included:

1. Feature scaling using StandardScaler
2. Determining optimal clusters using the **Elbow Method**
3. Applying **K-Means clustering**
4. Assigning cluster labels to customers

Customers were grouped based on their purchasing behavior.

---

# Customer Segments Identified

The clustering algorithm identified several customer segments, including:

### High-Value Customers
- Frequent purchases
- High spending
- Strong engagement

### Loyal Customers
- Regular purchases
- Moderate spending

### At-Risk Customers
- Previously active but recently inactive

### Low-Value Customers
- Infrequent purchases
- Low spending

---

# Key Insights

1. A small percentage of customers generate a large portion of revenue.

2. High-value customers purchase more frequently and spend significantly more per transaction.

3. Some customers show declining activity, indicating potential churn risk.

4. Customer segmentation provides a clearer understanding of purchasing patterns across the customer base.

---

# Business Recommendations

Based on the analysis, businesses should:

### Target High-Value Customers
Offer loyalty programs and exclusive offers to retain high-value customers.

### Re-engage At-Risk Customers
Use targeted promotions or personalized campaigns to reactivate customers.

### Improve Marketing Segmentation
Use customer clusters for more personalized marketing strategies.

### Focus Retention Efforts
Retaining existing customers is often more cost-effective than acquiring new ones.

---

# Project Structure
