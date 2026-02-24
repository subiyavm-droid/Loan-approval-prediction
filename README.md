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

1. Checked data types, missing values, and class distribution.
2. Visualized categorical features using count plots.

**Data Preprocessing**

1. Handled missing values using median (numerical) and mode (categorical).
2. Encoded categorical variables using Label Encoding.
3. Scaled features using StandardScaler for better model performance.

**Model Building**

1. Applied Logistic Regression for binary classification.
2. Used stratified train-test split to maintain class balance.

**Model Evaluation**

1. Evaluated model performance using Accuracy Score.
2. Analyzed results using Confusion Matrix and Classification Report.

📈 **Results**

1. The Logistic Regression model achieved an accuracy of approximately 80–85%.
2. Credit history and applicant income were found to be strong indicators of loan approval.

🛠️ **Tech Stack**
Programming Language: Python

Libraries Used:

Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Platform: Google Colab

📂 **Project Structure**

📁 Loan-Approval-Prediction │── Loan_Approval_Prediction.ipynb │── Loan_Approval_Prediction_Dataset.csv │── README.md

🚀 **Future Enhancements**
1. Implement advanced models like Random Forest and XGBoost
2. Perform hyperparameter tuning for improved accuracy
3. Deploy the model using Flask or Streamlit
4. Add feature importance analysis
