# Customer Churn Forecasting System

## Project Overview

Customer churn is one of the biggest challenges faced by subscription-based and service-oriented businesses. Acquiring new customers is significantly more expensive than retaining existing ones, making churn prediction an essential business strategy.

This project develops a **Customer Churn Forecasting System** using Machine Learning to predict whether a customer is likely to stop using a product or service. The solution includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and performance evaluation. The insights generated from the model can help businesses identify high-risk customers and implement proactive retention strategies.

---

# Objectives

* Predict customers who are likely to churn.
* Analyze customer behavior and identify churn patterns.
* Build and compare multiple machine learning models.
* Evaluate model performance using appropriate classification metrics.
* Provide actionable business recommendations to improve customer retention.

---

# Dataset Description

The dataset contains customer demographic information, account details, subscribed services, billing information, and churn status.

Typical features include:

* Customer ID
* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn (Target Variable)

**Target Variable**

* **Churn**

  * Yes = Customer left the service
  * No = Customer retained the service

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Joblib
* XGBoost (Optional)

---

# Project Structure

```
Customer-Churn-Prediction/

│── data/
│     └── customer_churn.csv

│── notebooks/
│     └── Customer_Churn_Prediction.ipynb

│── src/
│     ├── preprocessing.py
│     ├── feature_engineering.py
│     ├── train_model.py
│     ├── evaluate.py

│── models/
│     └── best_model.pkl

│── images/

│── README.md

│── requirements.txt

│── Customer_Churn_Report.pdf
```

---

# Workflow

## 1. Data Collection

* Import dataset
* Understand data structure
* Identify feature types

---

## 2. Data Preprocessing

The preprocessing stage includes:

* Removing duplicate records
* Handling missing values
* Converting data types
* Encoding categorical variables
* Feature scaling
* Removing unnecessary columns
* Handling class imbalance using SMOTE

---

## 3. Exploratory Data Analysis (EDA)

Several visualizations are created to understand customer behavior:

* Churn distribution
* Histograms
* Box plots
* Count plots
* Correlation heatmap
* Pair plots
* Monthly charge distribution
* Contract type analysis
* Tenure analysis

EDA helps identify the factors influencing customer churn.

---

## 4. Feature Engineering

Additional meaningful features are created to improve prediction performance, including:

* Customer tenure
* Service usage indicators
* Billing characteristics
* Customer engagement metrics

---

## 5. Machine Learning Models

The following classification algorithms are implemented and compared:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier
* XGBoost Classifier (Optional)

Hyperparameter tuning is performed using GridSearchCV to identify the best-performing model.

---

# Model Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix
* Classification Report
* ROC Curve
* Precision-Recall Curve

The best-performing model is selected based on overall predictive performance.

---

# Results

The project compares the performance of multiple machine learning models to identify the most effective approach for customer churn prediction. Evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC are used to assess each model's performance. The final selected model demonstrates strong predictive capability and effectively distinguishes customers who are likely to churn from those who are expected to remain.

---

# Business Insights

The analysis provides valuable business insights, including:

* Customers with month-to-month contracts are more likely to churn.
* Customers with shorter tenure exhibit a higher churn rate.
* Higher monthly charges are associated with increased churn probability.
* Customers without online security or technical support are more likely to leave.
* Automatic payment methods and long-term contracts contribute to improved customer retention.

These insights can guide businesses in designing targeted retention campaigns and improving customer satisfaction.

---

# Business Recommendations

Based on the model findings, the following strategies are recommended:

* Offer personalized retention plans for customers identified as high risk.
* Encourage customers to switch from month-to-month to long-term contracts.
* Provide discounts or loyalty rewards to customers with short tenure.
* Promote value-added services such as Online Security and Tech Support.
* Implement proactive customer engagement programs before contract renewal.

---

# Future Improvements

Potential enhancements include:

* Deploying the model as a web application using Flask or Streamlit.
* Integrating real-time customer data for live churn prediction.
* Applying deep learning techniques for improved predictive performance.
* Incorporating additional customer interaction and behavioral data.
* Building automated dashboards for business monitoring.

---

# Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Customer-Churn-Prediction.git
```

Navigate to the project folder:

```bash
cd Customer-Churn-Prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

# Running the Project

Run the Jupyter Notebook:

```bash
jupyter notebook Customer_Churn_Prediction.ipynb
```

Or execute the training script:

```bash
python train_model.py
```

---

# Output

The project generates:

* Cleaned dataset
* Trained machine learning model
* Feature importance analysis
* Evaluation metrics
* Confusion matrix
* ROC curve
* Precision-Recall curve
* Business insights
* Customer churn predictions

---

# Conclusion

This Customer Churn Forecasting System demonstrates how machine learning can be leveraged to predict customer attrition and support proactive retention strategies. By combining robust data preprocessing, exploratory analysis, feature engineering, and multiple predictive models, the project provides accurate churn predictions along with meaningful business insights. The solution enables organizations to identify at-risk customers early, optimize customer engagement efforts, and improve long-term customer retention and profitability.

---


Machine Learning | Data Science | Python
