# DL_Customer_Churn_Analysis

# 📊 Customer Churn Prediction using Keras

## 🧠 Project Overview

This project aims to **predict customer churn** for a telecom company named **Leo** using **Binary Classification** with **Keras (TensorFlow backend)**. Understanding why customers leave and predicting who is likely to churn can help the company take proactive steps to improve customer retention.

---

## 📝 Problem Statement

Leo, a telecom service provider, is facing a **high churn rate**. Your job as a Data Scientist is to:
- Analyze customer behavior,
- Identify key drivers of churn,
- Build a predictive model to classify whether a customer is likely to churn or not.

---

## 🧰 Technologies Used

- **Programming Language**: Python
- **Deep Learning Framework**: Keras (TensorFlow backend)
- **Libraries**: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## 🧪 Model Details

- **Model Type**: Binary Classification
- **Architecture**: Feedforward Neural Network (Sequential API)
- **Activation Functions**: ReLU, Sigmoid
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Evaluation Metric**: Accuracy

---

## 📈 Workflow

1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Feature scaling (Standardization/Normalization)

2. **EDA (Exploratory Data Analysis)**
   - Visualize churn distribution
   - Identify correlations and trends in features

3. **Model Building**
   - Define Neural Network architecture using Keras
   - Compile and train the model
   - Evaluate performance on test data

4. **Evaluation**
   - Confusion Matrix
   - Accuracy Score
   - Precision, Recall, F1-score
   - ROC-AUC Curve

---

## 🗂️ Dataset

The dataset contains customer data such as:
- `gender`, `senior_citizen`, `tenure`, `monthly_charges`, etc.
- The target variable is: `Churn` (Yes/No)

---

## 🔍 Insights

- Customers with high monthly charges and short tenure tend to churn more.
- Long-term customers are less likely to churn.
- Internet service, customer service calls, and contract type are influential features.

---

## 📌 Results

- **Training Accuracy**: ~79%
- **Validation Accuracy**: ~78%
- ROC-AUC score shows good discrimination capability.

---

## 💡 Business Impact

By using this predictive model, Leo Telecom can:
- Identify at-risk customers early,
- Launch targeted retention strategies,
- Reduce churn rate and improve customer lifetime value.

---

## 📎 Future Work

- Implement Hyperparameter tuning (GridSearchCV, RandomSearch)
- Try other algorithms (XGBoost, Random Forest)
- Deploy the model using Flask/Streamlit

---

## 🙌 Acknowledgements

Thanks to the open-source community and the Keras & TensorFlow teams for the awesome tools!

---

## 📬 Contact

**Kalaiselvi Maheshkumar**  
Data Scientist | [LinkedIn](https://linkedin.com/in/kalaiselvi-ganesan-6313a32a2) | [GitHub](https://github.com/kalai2315)

