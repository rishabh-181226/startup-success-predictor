# 🚀 Startup Success Prediction & Startup Segmentation using Machine Learning

## 📌 Overview

This project applies multiple **data mining** and **machine learning** techniques to analyze startup performance using a dataset containing funding, financial, operational, and founder-related attributes. The objective is to help investors and business stakeholders identify the factors that contribute to startup success, estimate revenue potential, and discover hidden startup segments.

The project was completed in three phases:

* **Business Understanding & Exploratory Data Analysis**
* **Predictive Modeling**
* **Advanced Data Mining (Supervised, Unsupervised & Hybrid Learning)**

---

# 🎯 Business Objectives

### 1️⃣ Startup Success Prediction

Predict whether a startup will:

* IPO
* Be Acquired
* Fail

### 2️⃣ Revenue Prediction

Estimate startup revenue based on operational and financial indicators.

### 3️⃣ Startup Segmentation

Identify hidden startup segments using clustering techniques to better understand different growth profiles.

---

# 📊 Dataset

The dataset contains **100,000 startup records** with **11 attributes**.

| Feature                  | Description                    |
| ------------------------ | ------------------------------ |
| funding_rounds           | Number of funding rounds       |
| founder_experience_years | Founder experience             |
| team_size                | Startup team size              |
| market_size_billion      | Market opportunity             |
| product_traction_users   | Active users/customer traction |
| burn_rate_million        | Operational spending           |
| revenue_million          | Startup revenue                |
| investor_type            | Investor category              |
| sector                   | Business sector                |
| founder_background       | Founder profile                |
| outcome                  | IPO / Acquisition / Failure    |

---

# ⚙️ Project Workflow

```
Business Understanding
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Model Development
        │
        ├──────────────┐
        ▼              ▼
Classification     Regression
        │
        ▼
Clustering
        │
        ▼
Hybrid Model
        │
        ▼
Model Explainability (SHAP)
```

---

# 📈 Exploratory Data Analysis

The project begins with extensive EDA to understand startup behavior.

### Visualizations Included

* Distribution plots
* Correlation heatmap
* Boxplots
* Pairplots
* Revenue distribution
* Success distribution
* Feature relationships
* PCA visualization
* Cluster visualization
* Feature importance
* SHAP summary plots
* ROC Curve
* Confusion Matrix

---

# 🛠 Data Preprocessing

The following preprocessing steps were performed:

* Missing value validation
* Label Encoding
* Log Transformation
* Feature Engineering
* Feature Scaling
* SMOTE for class imbalance
* Train-Test Split
* Cross Validation

---

# 🤖 Machine Learning Models

## Classification

* Logistic Regression
* Random Forest
* XGBoost
* CatBoost

Evaluation Metrics

* Accuracy
* Precision
* Recall
* Weighted F1 Score
* ROC-AUC
* Confusion Matrix

---

## Regression

* Linear Regression
* Random Forest Regressor

Evaluation Metrics

* RMSE
* R² Score

---

## Unsupervised Learning

* K-Means Clustering
* PCA
* Elbow Method

---

## Hybrid Learning

A hybrid approach was developed by:

1. Performing K-Means clustering
2. Creating cluster labels
3. Using cluster labels as additional features
4. Retraining the classification model

This experiment demonstrated that adding unsupervised features does not always improve predictive performance, highlighting the importance of feature relevance.

---

# 📊 Model Explainability

To improve transparency and interpretability, SHAP (SHapley Additive Explanations) was used.

SHAP helped identify the most influential variables contributing to startup success.

Top features included:

* Revenue
* Product Traction
* Funding Rounds
* Founder Experience
* Burn Rate

---

# 📈 Key Findings

* **XGBoost** achieved the best classification performance.
* **Random Forest Regressor** outperformed Linear Regression for revenue prediction.
* Revenue and product traction were the strongest indicators of startup success.
* Burn rate negatively impacted startup outcomes.
* Three distinct startup segments were identified using K-Means clustering.
* Hybrid learning provided valuable insights but did not outperform the standalone supervised model.

---

# 💻 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* CatBoost
* SHAP
* SMOTE
* K-Means Clustering
* PCA
* Matplotlib
* Seaborn
* Jupyter Notebook

---


# 🚀 Future Improvements

* Deep Learning models
* AutoML optimization
* Feature selection pipelines
* Time-series startup forecasting
* Interactive Streamlit dashboard
* Cloud deployment with Docker

---

# 📚 Learning Outcomes

Through this project I gained hands-on experience with:

* End-to-end Machine Learning pipelines
* Business problem formulation
* Feature engineering
* Classification & Regression
* Clustering techniques
* Explainable AI (SHAP)
* Model evaluation
* Data visualization
* Real-world investment analytics

---

# 👨‍💻 Author

**Rishabh Gupta**

**M.S. Business Analytics**

University of Louisville

---

## ⭐ If you found this project interesting, consider giving it a star!
