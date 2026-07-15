# Flipkart Customer Satisfaction (CSAT) Prediction using Machine Learning

## Project Overview

This project aims to analyze Flipkart customer service data and predict Customer Satisfaction (CSAT) using Machine Learning techniques. The objective is to identify the factors that influence customer satisfaction and build a predictive model that helps improve customer service quality.

---

## Problem Statement

Customer satisfaction is a key performance indicator for any e-commerce platform. This project analyzes customer service interactions and predicts CSAT scores based on operational and service-related features such as response time, agent shift, tenure, item price, and communication channels.

---

## Objectives

- Analyze customer service data using Exploratory Data Analysis (EDA)
- Identify factors affecting customer satisfaction
- Preprocess and clean the dataset
- Perform feature engineering and feature selection
- Build multiple Machine Learning classification models
- Compare model performance
- Select the best-performing model
- Save the trained model for deployment

---

## Dataset Features

The dataset contains customer service information including:

- Channel Name
- Category
- Sub-Category
- Customer Remarks
- Item Price
- Agent Name
- Supervisor
- Manager
- Tenure Bucket
- Agent Shift
- Response Time
- CSAT Score

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Joblib

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Missing Value Handling
4. Outlier Detection
5. Text Preprocessing
6. Feature Engineering
7. Feature Selection
8. Data Transformation
9. Data Scaling
10. Train-Test Split
11. Handling Imbalanced Data using SMOTE
12. Model Building
13. Model Evaluation
14. Hyperparameter Tuning
15. Model Comparison
16. Model Saving

---

## Exploratory Data Analysis

The project includes visualizations such as:

- CSAT Score Distribution
- Response Time Distribution
- Agent Shift Analysis
- Channel-wise CSAT
- Category-wise CSAT
- Manager Performance
- Tenure vs CSAT
- Correlation Heatmap
- Pair Plot
- Scatter Plot
- Heatmaps
- Count Plots
- Line Charts

---

## Machine Learning Models

Three classification models were implemented:

### 1. Logistic Regression

- Baseline classification model
- Hyperparameter tuning using GridSearchCV

### 2. Random Forest Classifier

- Ensemble learning model
- Hyperparameter tuning using GridSearchCV

### 3. Gradient Boosting Classifier

- Sequential ensemble model
- Hyperparameter tuning using GridSearchCV
- Selected as the final model

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Cross Validation

---

## Hyperparameter Tuning

GridSearchCV was used to optimize model parameters and improve predictive performance.

---

## Model Deployment

The final trained model was saved using Joblib for future deployment.

```python
joblib.dump(best_gb, "best_gradient_boosting_model.joblib")
```

---

## Results

- Successfully analyzed customer satisfaction data.
- Identified important factors affecting CSAT.
- Built and compared three machine learning models.
- Improved model performance using GridSearchCV.
- Selected Gradient Boosting Classifier as the final prediction model.
- Saved the trained model for deployment.

---

## Future Scope

- Deploy the model using Flask or Streamlit.
- Build a real-time customer satisfaction prediction dashboard.
- Integrate customer feedback sentiment analysis.
- Improve prediction accuracy using advanced ensemble methods.

---

## Repository Structure

```
├── data/
│   └── flipkart_csat.csv
│
├── notebooks/
│   └── Flipkart_Sales_Analysis ML file.ipynb
│   
|
├── README.md
│
└── requirements.txt
```

---

## Author

**Mohammad Sajjaduddin**

GitHub: https://github.com/Mohammad-Sajjaduddin


---

## License

This project is created for educational and portfolio purposes.
