# Project Overview
This project analyzes customer churn in a telecommunications company using machine learning techniques. The goal is to identify factors contributing to customer churn and build a predictive model to help the company retain customers.
# Dataset

The dataset used for this project includes customer demographics, account information, and service usage details. Key features include:
- Customer ID
- Tenure (length of service)
- Monthly charges
- Total charges
- Contract type (Month-to-Month, One year, Two years)
- Payment method
- Internet service type
- Dependents and partner status
- Churn (Target variable: Yes/No)

# Tools and Technologies
The project was implemented using:
- Python (pandas, numpy, scikit-learn, matplotlib)
- Jupyter Notebook for exploratory data analysis (EDA)
- **Machine Learning Models:** Logistic Regression, Support Vector Machine (SVM), and Random Forest
- **Feature Engineering & Data Preprocessing:**  encoding categorical variables, and feature scaling
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score

# Model Building and Results

- **Baseline Model:** Logistic Regression achieved an accuracy of ~82%.
- Improved Model: Random Forest and SVM performed reasonably, achieving an accuracy of 80% and 79% respectively.
- Feature Importance: Contract type and tenure were significant predictors of churn.
- Hyperparameter Tuning: Grid Search and Random Search were used for optimization.

# Key Findings
- Customers on month-to-month contracts have higher churn rates.
- Higher monthly charges contribute to customer churn.
- Customers with longer tenure are less likely to churn.
