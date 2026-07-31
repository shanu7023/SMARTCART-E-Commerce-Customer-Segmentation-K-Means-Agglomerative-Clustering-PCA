# 🛒 SMARTCART E-Commerce Customer Segmentation

This project demonstrates how **Machine Learning** can be used to segment customers of an e-commerce business based on their demographics, purchasing behavior, income, and spending patterns.

Customer segmentation helps businesses better understand their customers and enables personalized marketing campaigns, product recommendations, customer retention strategies, and targeted promotions.

The complete workflow includes:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Principal Component Analysis (PCA)
- K-Means Clustering
- Agglomerative Clustering
- Cluster Visualization
- Customer Cluster Analysis

---

# 📌 Project Objective

The objective of this project is to identify meaningful customer groups by analyzing customer demographics and purchase history.

The identified clusters can help businesses:

- Personalize marketing campaigns
- Identify high-value customers
- Improve customer retention
- Create targeted promotional offers
- Understand customer spending behavior

---

# 📊 Dataset Features

The dataset contains customer information such as:

- Customer Income
- Education
- Marital Status
- Date of Customer Enrollment
- Product Spending
- Number of Children
- Campaign Responses
- Purchase History
- Recency
- Web Purchases
- Store Purchases
- Catalog Purchases

---

# ⚙️ Project Workflow

## 1. Data Preprocessing

- Loaded dataset using Pandas
- Checked missing values
- Filled missing Income values using Median
- Converted customer joining date to datetime format

---

## 2. Feature Engineering

Created new features including:

- Age
- Customer Tenure
- Total Spending
- Total Children
- Simplified Education Categories
- Living With (Partner / Alone)

---

## 3. Data Cleaning

Removed unnecessary columns such as:

- Customer ID
- Birth Year
- Individual product spending columns
- Original marital status
- Customer joining date

Removed outliers from:

- Age
- Income

---

## 4. Exploratory Data Analysis

Performed:

- Pair Plot
- Correlation Heatmap
- Distribution Analysis

---

## 5. Feature Encoding

Categorical variables were converted using:

- One-Hot Encoding

Encoded features:

- Education
- Living_With

---

## 6. Feature Scaling

Applied:

- StandardScaler

to normalize numerical features before clustering.

---

## 7. Dimensionality Reduction

Applied **Principal Component Analysis (PCA)**

Reduced high-dimensional data into **3 Principal Components** for visualization and clustering.

---

## 8. Finding Optimal Number of Clusters

Two evaluation methods were used:

### Elbow Method

- WCSS (Within Cluster Sum of Squares)

### Silhouette Score

- Evaluates clustering quality

KneeLocator was used to identify the optimal value of **K**.

---

## 9. Clustering Algorithms

### K-Means Clustering

Used for partitioning customers into clusters based on feature similarity.

### Agglomerative Hierarchical Clustering

Performed hierarchical customer segmentation using Ward linkage.

---

## 10. Cluster Visualization

Visualized customer segments using:

- 3D PCA Scatter Plot
- Cluster Count Plot
- Income vs Total Spending Scatter Plot

---

## 11. Cluster Characterization

Generated cluster-wise averages to analyze:

- Income
- Spending
- Customer Age
- Recency
- Campaign Response
- Customer Tenure
- Number of Children

These insights help interpret the behavior of each customer segment.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- KNeed

---

# 📚 Machine Learning Techniques

- One-Hot Encoding
- Standard Scaling
- Principal Component Analysis (PCA)
- K-Means Clustering
- Agglomerative Clustering
- Elbow Method
- Silhouette Score

---

# 📈 Visualizations

The project includes:

- Pair Plot
- Correlation Heatmap
- PCA 3D Projection
- Elbow Curve
- Silhouette Score Curve
- Combined Evaluation Plot
- K-Means Cluster Visualization
- Agglomerative Cluster Visualization
- Cluster Distribution Plot
- Income vs Spending Analysis

---

# 📂 Project Structure

```
SMARTCART-Customer-Segmentation/
│
├── smartcart_customers.csv
├── smartcart.ipynb
├── README.md

```

---

# 🚀 Applications

Customer segmentation can be used for:

- Personalized Product Recommendations
- Customer Lifetime Value Analysis
- Loyalty Programs
- Customer Retention
- Targeted Advertising
- Premium Customer Identification
- Marketing Campaign Optimization

---

# 📌 Future Improvements

- DBSCAN Clustering
- Gaussian Mixture Models (GMM)
- Interactive Dashboard using Power BI
- Customer Recommendation System
- RFM Analysis
- Automated Cluster Interpretation

---

# 📖 Conclusion

This project demonstrates a complete end-to-end customer segmentation workflow using machine learning.

By combining feature engineering, dimensionality reduction, clustering algorithms, and visualization techniques, meaningful customer groups can be identified to support data-driven business decisions and targeted marketing strategies.

The project serves as a practical implementation of unsupervised machine learning techniques for real-world e-commerce customer analytics.
