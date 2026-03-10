# Netflix Customer Churn Prediction (Machine Learning)

## Project Overview

This project builds a machine learning model to predict whether a customer will **churn (leave the platform)** based on behavioral, demographic, and subscription-related features.

Customer churn prediction helps streaming platforms identify **at-risk users** and take proactive actions such as promotions, engagement campaigns, or personalized recommendations.

---

## Dataset

The dataset contains **1000 customers** with 16 features related to usage behavior and demographics.

### Key Features

* Subscription Length (Months)
* Customer Satisfaction Score
* Daily Watch Time
* Engagement Rate
* Device Used Most Often
* Genre Preference
* Region
* Payment History
* Subscription Plan
* Support Queries Logged
* Age
* Monthly Income
* Promotional Offers Used
* Number of Profiles Created

**Target Variable**

* Churn Status (Yes / No)

---

## Project Workflow

1. Data Loading and Inspection
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Encoding (One-Hot Encoding)
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Hyperparameter Tuning
9. Model Comparison

---

## Machine Learning Models Used

* Logistic Regression
* Random Forest
* XGBoost
* CatBoost

---

## Model Performance

| Model               | Accuracy        |
| ------------------- | --------------- |
| Logistic Regression | 0.48            |
| Random Forest       | 0.56            |
| XGBoost             | 0.54            |
| CatBoost            | **0.58 (Best)** |

CatBoost performed the best and was able to identify **70% of churn customers (recall = 0.70)**.

---

## Key Insights

* Customer churn behavior depends on **multiple factors rather than a single feature**.
* Tree-based models performed better than linear models.
* CatBoost achieved the best overall performance for this dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* CatBoost
* Matplotlib
* Seaborn

---

## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/netflix-churn-ml.git
```

2. Install required libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost catboost
```

3. Run the notebook

```bash
jupyter notebook ML.ipynb
```

---

## Future Improvements

* Use larger real-world datasets
* Apply feature engineering
* Deploy the model using a web application

---

## Author

Aiswarya T
