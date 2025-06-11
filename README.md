# 🏬 Customer Segmentation Using K-Means Clustering

## 📌 Overview
This repository contains a machine learning project that segments **mall customers** into distinct groups using **K-Means clustering**. Understanding customer behavior helps businesses tailor marketing strategies, improve services, and boost sales. 💡

## 📊 Dataset
The dataset includes details about mall customers:

| Feature | Description |
|---------|------------|
| 🆔 **CustomerID** | Unique ID assigned to each customer |
| 🚻 **Gender** | Customer gender (Male/Female) |
| 🕰 **Age** | Customer's age |
| 💰 **Annual Income (k$)** | Yearly income (in thousand dollars) |
| 🎯 **Spending Score (1-100)** | Customer's spending habit score (higher = spends more) |

## 🛠 Dependencies
Before running the project, install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## 🏗 Model Training
The segmentation process follows these key steps:
1. 🧹 **Data Preprocessing** – Handling missing values, encoding categorical variables, and scaling features.
2. 📊 **Exploratory Data Analysis (EDA)** – Visualizing customer distributions and patterns.
3. 🤖 **K-Means Clustering** – Applying K-Means to group customers based on spending behavior and income.
4. 🖼 **Visualization** – Using **scatter plots** and **centroid analysis** to interpret customer clusters.


## 📈 Results
The model classifies customers into segments based on spending patterns and income, helping businesses target marketing strategies effectively. 🛍

Key results:
- ✅ **Optimal number of clusters (Elbow Method)**
- 📊 **Customer segmentation visualization**
- 🔍 **Insights into customer behavior**

## 🔮 Future Improvements
Possible enhancements:
- 🛠 **Fine-tuning cluster numbers** using advanced techniques
- 🏆 **Alternative clustering methods** (e.g., DBSCAN, Hierarchical Clustering)
- 📡 **Integrating real-time customer data for dynamic segmentation**

## 💡 Contributing
Feel free to fork the repository and submit pull requests with improvements. 🚀
