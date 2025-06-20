# Customer Churn Prediction using Keras

https://9bbd-34-16-184-0.ngrok-free.app/

![Uploading image.png…]()



## Project Overview

This project focuses on predicting customer churn for a telecom company named **Leo** using a **binary classification model** built with **Keras**. The goal is to proactively identify customers who are likely to leave the service, allowing the business to take retention actions.

---

## Problem Statement

The telecom company, Leo, has been losing customers to competitors. As a Data Scientist, your role is to:
- Analyze the customer data,
- Identify key patterns and features leading to churn,
- Build a machine learning model to predict whether a customer will churn.

---

## Technologies and Tools

- **Language:** Python  
- **Libraries & Frameworks:**  
  - Pandas, NumPy  
  - Matplotlib, Seaborn  
  - Scikit-learn  
  - TensorFlow/Keras  
- **Model Evaluation:** Accuracy, Confusion Matrix, Classification Report, ROC-AUC

---

## Dataset Description

The dataset includes various customer-related features such as:
- Demographics (gender, senior citizen status)
- Services signed up for (internet service, phone service, etc.)
- Account information (contract type, tenure, monthly charges)
- Target variable: `Churn` (Yes/No)

---

## Project Steps

### 1. Data Preprocessing
- Handled missing values and irrelevant columns
- Encoded categorical variables
- Performed feature scaling

### 2. Exploratory Data Analysis (EDA)
- Churn distribution
- Key features contributing to churn
- Correlation analysis and visual insights

### 3. Model Building
- Created a deep learning model using **Keras Sequential API**
- Used `ReLU` for hidden layers and `Sigmoid` for output layer
- Compiled with `binary_crossentropy` loss and `adam` optimizer

### 4. Model Evaluation
- Accuracy on test set
- Confusion Matrix
- Precision, Recall, F1-score
- ROC-AUC score and curve

---

## Key Findings

- Customers with short tenure and high monthly charges are more likely to churn.
- Long-term contracts and paperless billing show significant influence on churn probability.
- Internet service type and customer support experience are strong churn indicators.

---

## Results

- Model Accuracy: ~79%
- ROC-AUC Score: High model discrimination ability
- Balanced performance across classes in classification report

---

## Business Use Case

By deploying this model, Leo can:
- Predict churn probability for each customer
- Implement targeted marketing campaigns
- Optimize customer service and retention strategies

---

## Future Improvements

- Use hyperparameter tuning (GridSearchCV or RandomSearch)
- Try ensemble models like Random Forest and XGBoost
- Deploy using Streamlit or Flask for real-time predictions

---

## Author

**Kalaiselvi Maheshkumar**  
Data Scientist  
LinkedIn: [kalaiselvi-ganesan-6313a32a2](https://linkedin.com/in/kalaiselvi-ganesan-6313a32a2)  
GitHub: [kalai2315](https://github.com/kalai2315)

