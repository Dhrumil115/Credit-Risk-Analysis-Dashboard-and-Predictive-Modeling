# Credit Risk Analysis

Credit risk analysis is an essential component of modern financial services, enabling lenders to predict the likelihood of borrowers defaulting on their loans. This project aims to utilize data-driven techniques to assess credit risk by developing machine learning models. The analysis helps lenders better understand patterns in loan data and make more informed credit decisions.
## Abstract
In this project, we carried out a detailed analysis of credit risk by applying machine learning models on a curated dataset. After performing data cleaning, exploratory data analysis (EDA), and feature engineering, we built several models including Random Forest, Decision Tree, and Logistic Regression. Among these, the Random Forest classifier achieved the highest accuracy of 95%. The project highlights the importance of features such as loan amount, interest rates, and annual income in predicting loan defaults, providing valuable insights for optimizing credit risk strategies.

## Project Overview

The analysis involves:
- Data Cleaning and Pre-processing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training and Evaluation (Random Forest, Decision Tree, and Logistic Regression)
- Comparison of model performances

## Dataset

The dataset used in this analysis comes from a public source and includes the following key features:
- Loan Amount
- Interest Rate
- Annual Income
- Home Ownership
- Employment Length
- Loan Status, etc.

The cleaned dataset (Cleaned_CreditRisk_Loan.csv) is included in the repository.

## Exploratory Data Analysis

During EDA, we visualized the distribution of loan amounts, interest rates, and annual income. Correlation analysis was performed to examine relationships between variables.

Visualizations:
- Loan Amount vs Interest Rate
- Correlation Matrix
- Home Ownership Distribution

## Models Used

1. **Random Forest Classifier**
2. **Decision Tree Classifier**
3. **Logistic Regression**

All models were trained and evaluated on a cleaned dataset, using accuracy, confusion matrix, and classification report as evaluation metrics.

### Results

| Model               | Accuracy (%) |
|---------------------|--------------|
| Random Forest       | 95.00        |
| Decision Tree       | 92.00        |
| Logistic Regression | 89.50        |

The best performing model was the Random Forest Classifier with 95% accuracy.

## Dependencies

This project uses the following Python libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
