# 🚲 Machine Learning Capstone Project

## London Bike Sharing — End-to-End ML Analysis

**Dataset:** [London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset) — TfL Open Data  
**Tools:** Python, Scikit-learn, TensorFlow/Keras, Statsmodels, Pandas, Matplotlib, Seaborn

---

## 📁 Project Structure
- `part1_regression/` — Predict hourly ride count
- `part2_classification/` — Predict high/low demand hours
- `part3_timeseries/` — Forecast future ride counts
- `part4_clustering/` — Discover riding pattern groups

---

## 📊 Part 1 — Regression
**Best Model:** Random Forest (RMSE: 228, R²: 0.956)  
**Models:** Linear Regression, Lasso, Ridge, SVR, Decision Tree, Random Forest, Neural Network

---

## 🎯 Part 2 — Classification
**Best Model:** Neural Network (F1: 0.947, Accuracy: 94.7%)  
**Models:** Logistic Regression, SVC, Decision Tree, Random Forest, Neural Network

---

## 📈 Part 3 — Time Series
**Best Method:** LSTM (RMSE: 181) + Random Forest Lag Features (MAE: 107)  
**Methods:** Holt-Winters, Random Forest + Lag Features, LSTM

---

## 🔵 Part 4 — Clustering
**Best Algorithm:** Agglomerative Clustering (Silhouette: 0.3326)  
**Algorithms:** K-Means, DBSCAN, Agglomerative Clustering

---

## 🚀 How to Run
1. Clone the repo
2. Install: `pip install pandas numpy matplotlib seaborn scikit-learn tensorflow statsmodels`
3. Open any notebook in VS Code and run all cells
