💳 **Loan Approval Prediction** 

📌 **Project Overview**

This project focuses on predicting whether a loan application will be approved or rejected based on applicant details such as income, education, employment status, credit history, and property area. The objective is to build a reliable machine learning model that assists financial institutions in automating loan approval decisions.

📊 **Dataset Description**

The dataset contains 614 loan applications with both numerical and categorical features.

**Key Features:**

1. Numerical: Applicant Income, Coapplicant Income, Loan Amount, Loan Amount Term, Credit History
2. Categorical: Gender, Married, Dependents, Education, Self Employed, Property Area
3. Target Variable: Loan_Status (Approved / Not Approved)

⚙️ **Project Workflow**

**Data Loading**

Imported dataset using Pandas.

**Exploratory Data Analysis (EDA)**

Checked data types, missing values, and class distribution.
Visualized categorical features using count plots.

**Data Preprocessing**

Handled missing values using median (numerical) and mode (categorical).
Encoded categorical variables using Label Encoding.
Scaled features using StandardScaler for better model performance.

**Model Building**

Applied Logistic Regression for binary classification.
Used stratified train-test split to maintain class balance.

**Model Evaluation**

Evaluated model performance using Accuracy Score.
Analyzed results using Confusion Matrix and Classification Report.

📈 **Results**

The Logistic Regression model achieved an accuracy of approximately 80–85%.
Credit history and applicant income were found to be strong indicators of loan approval.

🛠️ **Tech Stack**
Programming Language: Python

Libraries Used:

Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Platform: Google Colab

📂 P**roject Structure**
📁 Loan-Approval-Prediction │── Loan_Approval_Prediction.ipynb │── Loan_Approval_Prediction_Dataset.csv │── README.md

🚀 **Future Enhancements**
Implement advanced models like Random Forest and XGBoost
Perform hyperparameter tuning for improved accuracy
Deploy the model using Flask or Streamlit
Add feature importance analysis
