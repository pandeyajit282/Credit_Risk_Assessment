# Credit_Risk_Assessment

The Loan Approval Prediction System is a data science project aimed at creating an accurate model for predicting loan approval outcomes. By analyzing applicant data, the system enables responsible lending decisions, minimizes financial risks for lending institutions, and enhances the overall loan approval process.

# Data Description

The dataset was taken from kaggle, and it contains following features
- ID: Unique identifier for each loan applicant.
- Age: Age of the loan applicant.
- Income: Income of the loan applicant.
- Home: Home ownership status (Own, Mortgage, Rent).
- Emp_Length: Employment length in years.
- Intent: Purpose of the loan (e.g., education, home improvement).
- Amount: Loan amount applied for.
- Rate: Interest rate on the loan.
- Status: Loan approval status.
- Percent_Income: Loan amount as a percentage of income.
- Default: Whether the applicant has defaulted on a loan previously (Yes, No).
- Cred_Length: Length of the applicant's credit history.

# Data Preprocessing 

- Handled missing values, outliers (IQR method) in the dataset and scaled the features using Min-max scaler.
- Converted categorical variables into numerical representations for machine learning algorithms, used one hot encoding.
- Handled imbalanced dataset and applied oversampling for it.

# Model building 

Tried multiple models like Logistic, KNN, Random forest, AdaBoost, and XGBoost. The random forest and XGBoost models had the highest accuracy.
Also performed hyperparameter tuning for random forest since it was overfitting. at the end XGBoost was selected as the final model.
