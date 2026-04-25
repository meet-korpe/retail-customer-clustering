# 📊 Retail Customer Clustering using Hierarchical Clustering

## 👨‍💻 Author

**Meet Korpe**

---

## 📌 Project Overview

Retail businesses often deal with customers having different purchasing patterns across product categories such as Fresh, Milk, Grocery, Frozen, Detergents & Delicatessen.

The objective of this project is to apply **Unsupervised Machine Learning (Hierarchical Clustering)** to group customers based on their **product spending behaviour**.

Customer segmentation helps businesses in:

* Targeted Marketing
* Inventory Optimization
* Product Placement Strategy
* Sales Improvement
* Customer Behaviour Understanding

---

## 🎯 Problem Statement

To analyze customer purchase data from a wholesale retail dataset and group similar customers together using **Hierarchical Clustering**, enabling retailers to take better data-driven business decisions.

---

## 📂 Dataset Description

The dataset contains annual spending of customers on different product categories.

### Features:

* **Fresh** – Annual spending on fresh products
* **Milk** – Annual spending on milk products
* **Grocery** – Annual spending on grocery items
* **Frozen** – Annual spending on frozen products
* **Detergents_Paper** – Spending on cleaning products
* **Delicatessen** – Spending on ready-to-eat food
* **Channel** – Customer type
* **Region** – Customer region

---

## ⚙️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

---

## 📊 Project Workflow

1. Data Loading
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Log Transformation (Handling Skewness)
5. Feature Scaling
6. Dendrogram Analysis
7. Hierarchical Clustering Model
8. Cluster Profiling
9. PCA Visualization
10. Business Insights

---

## 🤖 Machine Learning Algorithm Used

### Hierarchical Clustering (Agglomerative)

* Groups customers based on similarity
* Does not require labelled data
* Dendrogram used to determine optimal clusters

---

## 📈 Model Evaluation

* **Silhouette Score** used to evaluate clustering quality
* PCA used for cluster visualization

---

## 📌 Key Business Insights

* Some clusters represent **bulk grocery and milk buyers**, such as supermarkets
* Some clusters represent **fresh product buyers**, such as restaurants and hotels
* Balanced spending clusters indicate **medium-scale retailers**
* Low spending clusters indicate **small or occasional buyers**

These insights help businesses:

* Design targeted promotions
* Improve inventory management
* Optimize store layout
* Increase profitability

---

## 🚀 How to Run This Project

1. Clone the repository

```bash
git clone https://github.com/meet-korpe/retail-customer-clustering.git
```

2. Open the project folder

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run **Retail_Clustering.ipynb**

---

## 🔮 Future Improvements

* Compare with KMeans Clustering
* Deploy clustering dashboard using Streamlit
* Add real-time retail dataset
* Implement recommendation system

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

---
