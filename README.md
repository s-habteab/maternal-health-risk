## Predicting Maternal Health Risk Using Machine Learning

### Project Overview

This project aims to predict maternal health risks based on a dataset from UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/863/maternal+health+risk

The goal is to predict the health risk level of mothers during pregnancy using machine learning models.

### Technologies Used
- **pandas**, **numpy** – Data manipulation and analysis.
- **scikit-learn** – Machine learning algorithms and model evaluation.
- **matplotlib**, **seaborn** – Data visualization.

### Models Implemented
- **Ordinal Logistic Regression**
- **Random Forest**
- **XGBoost**

### Key Steps in the Project
- Exploratory Data Analysis (EDA) and data visualization.
- Feature Encoding and Feature Importance analysis.
- Data Splitting: The data is split into training and testing sets to evaluate model performance.
- Hyperparameter tuning for model optimization.
  
### Model Evaluation and Results
- Best Model: **XGBoost**, which slightly outperformed Random Forest.
- Lowest Accuracy: Ordinal Logistic Regression.
- Evaluation Metrics:
        Classification Reports and Confusion Matrices were used to assess model performance.

### How to Run
- Clone the repository.
- Install dependencies: pip install -r requirements.txt.
- Download the dataset from the UCI Machine Learning Repository.
- Run the Jupyter notebook: maternal_health_risk.ipynb
