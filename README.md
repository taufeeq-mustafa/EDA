# 📊 Aerofit Dataset – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the **Aerofit dataset**, which contains customer information related to treadmill purchases.  
The analysis aims to uncover patterns, trends, and insights that help understand customer behavior and product preferences.

---

## 📂 Dataset Information
The Aerofit dataset includes demographic and fitness-related attributes of customers.

### 🔑 Features Description
- **Product**: Treadmill model purchased (KP281, KP481, KP781)
- **Age**: Age of the customer
- **Gender**: Male / Female
- **Education**: Years of education
- **MaritalStatus**: Single / Partnered
- **Usage**: Average workouts per week
- **Fitness**: Self-rated fitness level (1–5)
- **Income**: Annual income of the customer
- **Miles**: Average miles run per week

---

## 🎯 Objectives
- Analyze customer demographics
- Understand product-wise customer behavior
- Identify relationships between fitness, income, and usage
- Extract meaningful business insights

---

## 🛠️ Tech Stack

### 💻 Programming Language
- Python

### 📚 Libraries Used
- **NumPy** – Numerical operations
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations

---

## 📈 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Histograms for Age, Income, and Miles
- Count plots for Gender, Product, and Marital Status
- Box plots to detect outliers

### 🔹 Bivariate Analysis
- Box plots of Income vs Product
- Count plots of Product vs Gender
- Scatter plots of Miles vs Income
- Bar plots of Usage vs Product

### 🔹 Multivariate Analysis
- Pair plots for numerical features
- Correlation heatmap

---

## 📊 Visualizations Used
- Histogram
- Box Plot
- Count Plot
- Scatter Plot
- Bar Plot
- Pair Plot
- Heatmap

---

## 🔍 Key Insights
- Customers purchasing **KP781** generally have higher income and fitness levels
- **KP281** is preferred by beginners with lower usage and fitness scores
- Males tend to run more miles per week on average
- Income is positively correlated with miles run and treadmill type
- Fitness level strongly correlates with usage frequency

---

## 📉 Correlation Summary
- **Miles ↔ Fitness**: Strong positive correlation
- **Usage ↔ Fitness**: Customers exercising more rate themselves fitter
- **Income ↔ Product**: Higher income customers prefer premium products

---

## ✅ Conclusion
The EDA reveals meaningful insights into customer behavior and treadmill preferences.  
These insights can help Aerofit:
- Improve targeted marketing
- Recommend suitable products
- Enhance customer segmentation strategies

---

## 🚀 Future Scope
- Feature engineering
- Predictive modeling
- Customer segmentation using clustering algorithms

---

## ▶️ How to Run the Project
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn

