# Netflix User Segmentation using K-Means

## 📌 Overview
This project focuses on analyzing Netflix user behavior and segmenting users into different groups based on their activity and preferences. The goal is to identify patterns in user engagement such as watch time, subscription type, and content preferences.

---

## 🎯 Objectives
- Perform data cleaning and preprocessing
- Analyze user behavior patterns
- Apply machine learning (K-Means clustering) to segment users
- Identify high, medium, and low engagement users

---

## 📊 Dataset
The dataset contains synthetic Netflix user data with the following features:
- Age
- Country
- Subscription Type (Basic, Standard, Premium)
- Watch Time (hours)
- Favorite Genre

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn (KMeans)
- Matplotlib & Seaborn
- PySpark (basic data processing)

---

## 🧩 Project Workflow

### 1. Data Preprocessing
- Removed unnecessary columns
- Handled missing values
- Converted categorical data into numeric format

### 2. Feature Selection
Used key features:
- Age
- Country
- Subscription Type
- Watch Time
- Favorite Genre

### 3. Clustering (K-Means)
- Applied K-Means algorithm with 3 clusters
- Grouped users based on behavior patterns

### 4. Analysis
- Compared clusters using average values
- Identified user engagement levels

### 5. Visualization
- Cluster distribution
- Watch time comparison across clusters

### 6. PySpark Implementation
- Loaded dataset using PySpark
- Performed basic aggregations (groupBy)
- Demonstrated scalable data processing

---

## 📈 Key Insights
- Identified distinct user segments based on watch time and subscription type
- High engagement users showed significantly higher watch time
- Subscription type influenced user behavior patterns
- Genre preferences varied across clusters

---

## 📂 Project Structure
```
Netflix-User-Segmentation/
│
├── notebook.ipynb
├── netflix_users.csv
├── netflix_users_clustered.csv
└── README.md
```

---

## 🚀 How to Run
1. Install dependencies:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn pyspark
```


2. Run the Jupyter Notebook:
   ```bash
   notebook.ipynb

## 🧠 Conclusion
This project demonstrates how user data can be analyzed and segmented using machine learning techniques. The insights can be used for personalization, recommendation systems, and targeted marketing strategies.


