# 🚕 An Ensemble Machine Learning Model for Predictive Analysis of Uber Pickups
### 📄 *Published in IEEE APCIT 2024 | Urban Mobility Analytics | Machine Learning*

**🔗 IEEE Paper Link:** https://ieeexplore.ieee.org/document/10673705  
**📘 Conference:** Asia Pacific Conference on Innovation in Technology (APCIT), Mysuru, India, July 2024  

This repository contains the full machine learning workflow and research implementation used in our IEEE-published study.  
The project focuses on predicting Uber pickup demand using **ensemble learning techniques**, evaluating multiple ML models, and identifying the most accurate predictor.

---

## ⭐ 1. Overview

Accurate prediction of Uber ride demand improves:

- Fleet allocation  
- Passenger wait-time reduction  
- Driver route optimization  
- City-level transportation planning  

Our research applies predictive analytics to Uber's New York pickup dataset and evaluates several machine learning models.  
**XGBoost emerged as the best-performing algorithm**, achieving the highest accuracy among all models tested.

---

## 🎯 2. Key Features of the Study

✔ Data preprocessing & cleaning  
✔ Feature extraction using **PCA (Principal Component Analysis)**  
✔ Comparative analysis of ML models  
✔ Performance evaluation using industry metrics  
✔ Visualization of Uber ride trends  
✔ Insights for urban mobility prediction  

---

## 🤖 3. Machine Learning Models Evaluated

The following models were implemented and compared:

- **XGBoost (Best Performer)**
- Gradient Boosting
- AdaBoost
- Bagging (Extra Trees)
- K-Nearest Neighbors (KNN)

These models were evaluated using metrics described in the IEEE paper (p.4–5) :contentReference[oaicite:1]{index=1}.

### 📊 Evaluation Metrics

- **R² Score**
- **MAE – Mean Absolute Error**
- **MSE – Mean Squared Error**
- **RMSE – Root Mean Squared Error**

---

## 📅 4. Dataset Information

Dataset Source: **Kaggle – Uber Pickups NYC**  
(Referenced in Section III-A of the paper) :contentReference[oaicite:2]{index=2}  

### Contains:

- **10,000+ records**
- Features:
  - Date  
  - Month  
  - Day  
  - Hour  
  - Weekday  
  - Cluster (location zone)  
  - Ride Count (Target Variable)

Sample dataset image shown on page 3 of the paper :contentReference[oaicite:3]{index=3}.

---

## 🧠 5. Best Performing Model — **XGBoost**

Based on experimental analysis (Table II in the paper, page 5) :contentReference[oaicite:4]{index=4}:

### 🥇 **XGBoost Accuracy Metrics**

| Metric | Value |
|-------|-------|
| **R² Score** | **0.99** |
| **MAE** | **6.629** |
| **MSE** | **0.53** |
| **RMSE** | **0.728** |

📌 *XGBoost outperformed all other models due to its strong handling of non-linear relationships, regularization, and robustness to feature noise.*

---

## 📊 6. Experimental Results

### 🔍 Model Comparison

(From Table II, page 5 of the paper) :contentReference[oaicite:5]{index=5}

| Model                     | R² Score |    MAE |    MSE |   RMSE |
|-------------------------- | -------- | ------ | ------ | ------ |
| **XGBoost**               | **0.99** | **6.629** | **0.53** | **0.728** |
| Gradient Boosting         | 0.96     | 12.45  | 1.89   | 1.374  |
| AdaBoost                  | 0.95     | 13.02  | 2.11   | 1.452  |
| Bagging (Extra Trees)     | 0.92     | 15.78  | 3.02   | 1.737  |
| KNN                       | 0.89     | 18.11  | 4.21   | 2.052  |

### 📈 Visual Insights from the Paper

Figures on page 5–6 show key patterns:  
- **Ride count increases steadily toward the end of April**  
- **September shows the highest ride activity overall**  
- Training and testing error graphs illustrate PCA component performance (page 6) :contentReference[oaicite:6]{index=6}  

---

## 🧪 7. Methodology (Pipeline Summary)

The full methodology (Section III, pages 2–4) :contentReference[oaicite:7]{index=7} includes:

### 🔹 Data Preprocessing
- Handling missing values  
- Label encoding categorical fields  
- Feature scaling using MinMax Scaler  

### 🔹 PCA-Based Feature Extraction
- Covariance matrix computation  
- Eigenvalue decomposition  
- Dimensionality reduction from *n* → *k* components  

### 🔹 Model Training & Evaluation
- Training multiple ensemble regressors  
- Performance comparison across PCA/LDA components  
- Hyperparameter tuning for best results  

---

## 🛠️ 8. Technologies Used

- **Python**
- **Pandas, NumPy**
- **Scikit-Learn**
- **XGBoost**
- **PCA (Dimensionality Reduction)**
- **Matplotlib & Seaborn**

---

## 🔗 Connect With Me

👨‍💻 **Revanth**  
🌐 LinkedIn: www.linkedin.com/in/revanthsaikumarmanyam  
💻 GitHub: https://github.com/revanth179 
