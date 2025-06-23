# 🏠 California Housing Price Prediction

A machine learning project that predicts house prices using the **California Housing** dataset.  
Implemented using two regression techniques:

- 📉 Linear Regression  
- 🤖 Support Vector Regression (SVR)

---

## 🔍 Dataset

- Source: `sklearn.datasets.fetch_california_housing()`
- 8 features describing housing data across districts in California
- Target: Median house value

---

## ⚙️ Techniques Used

| Model              | R² Score | Error Metric        |
|-------------------|----------|---------------------|
| Linear Regression | 0.58     | RMSE = 0.75         |
| SVR (RBF Kernel)  | 0.75     | MSE = 0.32          |

---

## 🧠 Why did SVR perform better?

Linear Regression assumes a straight-line (linear) relationship between features and price,  
but real-world housing data is often more complex and non-linear.  

Support Vector Regression (SVR) with an RBF kernel can model these non-linear relationships better,  
which led to lower prediction error and higher R² score compared to Linear Regression.

---

## 📊 Visualizations

This project includes several visualizations to explore and understand the dataset before and after modeling:

- 🔍 `histplot`: Distribution of key features
- 🔥 `heatmap`: Correlation matrix to identify relationships between variables
- 📦 `hist`: Raw distribution plots for each feature
- 👯 `pairplot`: Pairwise relationships between features
- 🎯 `scatter`: Actual vs Predicted Prices for model evaluation

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/california-housing-prediction.git
