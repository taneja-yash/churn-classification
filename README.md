# 🧠 Customer Churn Prediction
Customer churn is a major issue for businesses across industries. Retaining existing customers is often more cost-effective than acquiring new ones. This project aims to build a predictive model that identifies customers likely to churn, helping businesses take proactive retention measures.

## 📊 Project Overview
The goal of this project is to use historical customer data to predict whether a customer will leave (churn) or stay.
We explore the dataset, clean and preprocess it, build multiple classification models, and compare their performance to select the most accurate one.

## 🧩 Steps Involved
### 1. Data Understanding and Exploration
- Loaded the dataset and performed exploratory data analysis (EDA)
- Examined data distributions, correlations, and relationships between variables
- Visualized key insights using histograms, boxplots, and heatmaps

### 2. Data Preprocessing
- Handled missing values:
- Used median imputation for skewed numerical features
- Used mean imputation for normally distributed columns
- Encoded categorical variables
- Scaled numerical features for consistency across models
- Split the dataset into training and testing sets

### 3. Modeling
- Trained and evaluated multiple classification algorithms:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost / Gradient Boosting
- Support Vector Machine (SVM)
- Tuned hyperparameters for optimal performance

### 4. Model Evaluation
Compared models based on:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Chose the best-performing model for churn classification

### 5. Insights
- Identified the most influential features contributing to churn
- Derived actionable insights to help businesses improve customer retention strategies

## ⚙️ Tech Stack
- Language: Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost
- Environment: Jupyter Notebook / Google Colab

## 💡 Future Improvements
- Implement cross-validation and more robust hyperparameter tuning
- Try ensemble methods or neural network architectures
- Build an interactive dashboard in Tableau or Power BI for churn visualization
- Deploy the model using Flask or Streamlit


## Author
Yash Taneja
- [LinkedIn](https://linkedin.com/in/yash-taneja-07)
