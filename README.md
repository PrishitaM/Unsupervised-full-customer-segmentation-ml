# Unsupervised-full-customer-segmentation-ml
Implemented customer segmentation using K-Means and Agglomerative Hierarchical Clustering on standardized financial and behavioral data. Applied EDA, IQR-based outlier detection, and feature scaling, with model evaluation using Elbow Method and Silhouette Score to derive optimal clusters and actionable business insights.
Problem Statement

AllLife Bank aims to improve customer targeting, optimize support operations, and enhance digital adoption. This project applies unsupervised machine learning techniques to segment customers into meaningful groups.

## Dataset Overview
The dataset contains customer-level information including:

Average Credit Limit
Total Credit Cards
Bank Visits
Online Visits
Calls Made
## Exploratory Data Analysis (EDA)
Univariate and bivariate analysis performed using histograms, boxplots, and scatter plots
Identified right-skewed distributions and behavioral patterns in customer interactions
Correlation analysis confirmed low multicollinearity, making it suitable for clustering
## Data Preprocessing
✔️ No missing values detected
✔️ Outliers identified using IQR method and retained for business significance
✔️ Dropped irrelevant identifiers (Customer ID, Serial No)
✔️ Applied StandardScaler for feature normalization
## Modeling Approach
🔹 K-Means Clustering
Used Elbow Method and Silhouette Score to determine optimal clusters
Optimal number of clusters: K = 3
🔹 Hierarchical Clustering
Applied Agglomerative Clustering with multiple linkage methods
Evaluated using Dendrograms + Cophenetic Correlation
Final model: 3 clusters (Average Linkage)

## Results & Insights
Three distinct customer segments were identified:
Premium Digital Customers
High credit limit, high online activity
Low dependency on support → high-value segment
Traditional Mid-Value Customers
Moderate credit usage
Prefer branch visits → potential for digital migration
Low-Value High-Support Customers
Low credit limit, high call frequency
High operational cost → needs optimization
Business Recommendations
Target premium users with exclusive offers & retention strategies
Encourage mid-segment customers toward digital adoption
Reduce support cost for low-value users via self-service tools (chatbots, FAQs)

## Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

## Key Techniques Used
Exploratory Data Analysis (EDA)
Outlier Detection (IQR)
Feature Scaling (Standardization)
K-Means Clustering
Hierarchical Clustering
Silhouette Score & Elbow Method
## Key Takeaways
Successfully segmented customers into actionable groups
Demonstrated the effectiveness of unsupervised learning in business decision-making
Built a scalable segmentation framework for real-world applications
