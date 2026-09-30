# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project uses **K-Means Clustering** to segment customers based on their **Annual Income** and **Spending Score**.

The main goal is to group customers with similar spending behavior and income levels into different clusters.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* K-Means Clustering
* StandardScaler
* Jupyter Notebook

## 📂 Dataset

The project uses the **Mall Customers dataset** (`Mall_Customers.csv`).

The main columns used in this project are:

* **Age**
* **Annual Income (k$)**
* **Spending Score (1-100)**

## 🔍 Project Steps

### 1. Import Libraries

Imported Python libraries required for data analysis and machine learning.

### 2. Load the Dataset

Loaded the `Mall_Customers.csv` dataset using Pandas.

### 3. Data Understanding

Checked:

* Number of rows and columns
* Data types
* Statistical summary
* Missing values
* Duplicate values

### 4. Data Cleaning

Checked for duplicate records and removed duplicates where required.

### 5. Data Visualization

Created histograms to understand the distribution of:

* Age
* Annual Income
* Spending Score

### 6. Feature Selection

Selected the following features for customer segmentation:

* Annual Income
* Spending Score

### 7. Feature Scaling

Used **StandardScaler** to scale the selected features before applying K-Means clustering.

### 8. Finding the Optimal Number of Clusters

Used the **Elbow Method** and calculated WCSS for different values of K.

### 9. K-Means Clustering

Applied the K-Means algorithm with **5 clusters**.

### 10. Customer Segmentation

Assigned each customer to a cluster and added the cluster information to the dataset.

### 11. Visualization

Created a scatter plot to visualize the customer segments based on Annual Income and Spending Score.

### 12. Cluster Summary

Calculated the average:

* Age
* Annual Income
* Spending Score

for each customer cluster.

### 13. New Customer Prediction

Tested new customer data using the trained K-Means model to identify which cluster the customer belongs to.

## 📊 Key Analysis

The project identifies groups of customers based on their income and spending behavior.

The clusters can help understand different customer segments, such as customers with different combinations of income and spending scores.

## 🎯 Business Use

Customer segmentation can help businesses:

* Understand customer behavior
* Identify different customer groups
* Create targeted marketing strategies
* Improve customer engagement
* Make better business decisions

## 📁 Project Files

```text
Customer-Segmentation/
│
├── customer_segmentation.ipynb
├── Mall_Customers.csv
└── README.md
```

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Make sure Python is installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `customer_segmentation.ipynb`.
6. Make sure `Mall_Customers.csv` is in the same folder.
7. Run the notebook cells step by step.

## 👩‍💻 Author

**Sakshi Sonkusare**

This project was created as part of my practical learning in **Data Analysis and Machine Learning**.
