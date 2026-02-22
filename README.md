# Customer Segmentation using K-Means Clustering

## Project Overview
This project focuses on analyzing mall customer data to identify different customer groups based on their income levels and spending behavior. The main objective is to understand customer patterns and provide useful insights that can help businesses create more effective marketing strategies.

---

## Dataset Description
The dataset contains basic information about customers, including:

- Customer ID
- Gender
- Age
- Annual Income (in thousands of dollars)
- Spending Score (ranging from 1 to 100)

These attributes were used to study customer purchasing behavior.

---

## Methodology

### Data Exploration
Exploratory Data Analysis (EDA) was performed to understand the distribution of customer age, income, and spending patterns. Visualizations such as histograms and scatter plots were used to identify trends and relationships in the data.

### Feature Selection and Preprocessing
The key features selected for clustering were:
- Annual Income
- Spending Score

Data scaling was applied using StandardScaler to ensure that both features contributed equally to the clustering process.

### Clustering Approach
The K-Means clustering algorithm was used to segment customers into meaningful groups. The optimal number of clusters was determined using the Elbow Method.

---

## Results and Insights

The analysis successfully identified five distinct customer segments:

- Medium Customers – Customers with average income and spending behavior
- VIP Customers – High-income customers who spend significantly
- Impulsive Buyers – Customers with lower income but high spending habits
- Careful Spenders – High-income customers who spend cautiously
- Budget Customers – Customers with low income and low spending

---

## Business Recommendations

Based on the segmentation results, the following strategies can be applied:

- VIP customers can be targeted with loyalty programs and exclusive offers.
- Careful spenders can be encouraged through discounts and value-based promotions.
- Impulsive buyers can respond well to flash sales and limited-time deals.
- Budget customers can be attracted through affordable pricing strategies.

---

## Tools and Technologies Used

- Python
- Pandas and NumPy for data analysis
- Matplotlib and Seaborn for data visualization
- Scikit-learn for clustering implementation

---

## Conclusion

This project demonstrates how customer segmentation techniques can be used to better understand customer behavior and support data-driven decision-making in business environments.

---

## Author

Apoorva Srivastava
