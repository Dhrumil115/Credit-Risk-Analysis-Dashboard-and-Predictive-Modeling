# Credit Risk Analysis

Credit risk analysis is an essential component of modern financial services, enabling lenders to predict the likelihood of borrowers defaulting on their loans. This project aims to utilize data-driven techniques to assess credit risk by developing machine learning models. The analysis helps lenders better understand patterns in loan data and make more informed credit decisions.

## Abstract

In this project, we carried out a detailed analysis of credit risk by applying machine learning models on a curated dataset. After performing data cleaning, exploratory data analysis (EDA), and feature engineering, we built several models including Random Forest, Decision Tree, and Logistic Regression. Among these, the Random Forest classifier achieved the highest accuracy of 95%. The project highlights the importance of features such as loan amount, interest rates, and annual income in predicting loan defaults, providing valuable insights for optimizing credit risk strategies.


## 📌 Key Insights & Project Scope

This project focuses on analyzing a dataset of 80,000+ loan records to extract insights into loan performance, default rates, and borrower behavior. The workflow includes:

- Data Cleaning and Feature Engineering (Python, Pandas)
- Predictive Modeling (Random Forest, Logistic Regression, Decision Tree)
- Visualization (Power BI Dashboard)
- Web Deployment (HTML + AWS S3)

### 🧠 Key Insights

- **Total Loans Processed**: 80.47K  
- **Average Loan Amount**: $14K  
- **Default Rate**: 10.98%  
- **Top Loan Grades**: B and C carry the highest loan volumes  
- **Employment Length Impact**: Users with ≤1 year of employment show higher default rates

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

The cleaned dataset (`Cleaned_CreditRisk_Loan.csv`) is included in the repository.

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


## 📈 Dashboard Preview

The interactive Power BI dashboard visualizes all key metrics and trends and is hosted as a static website on AWS S3.

**[Click here to view the dashboard](http://credit-risk-analysis-dashboard.s3-website-us-east-1.amazonaws.com)**  
<br>
## Dependencies

This project uses the following Python libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
