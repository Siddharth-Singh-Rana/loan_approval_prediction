# Loan Approval Prediction 🏦✈️

An End-to-End Machine Learning Classification project to predict whether a loan application will be approved or rejected based on customer details like income, education, credit history, and loan amount.

## 🎯 Problem Statement & Objective
The goal of this project is to build a predictive model that automates the loan eligibility process for finance companies. Based on the historical data of applicants, the model classifies applications into **Approved (Y)** or **Rejected (N)**.

## 📊 Dataset Features Description
The dataset contains information about 614 applicants with 13 key attributes:
- `Loan_ID`: Unique Loan ID
- `Gender`: Male/Female
- `Married`: Applicant marital status (Yes/No)
- `Dependents`: Number of dependents (0, 1, 2, 3+)
- `Education`: Graduate / Not Graduate
- `Self_Employed`: Yes/No
- `ApplicantIncome`: Monthly income of the primary applicant
- `CoapplicantIncome`: Monthly income of the co-applicant
- `LoanAmount`: Loan amount in thousands
- `Loan_Amount_Term`: Term of loan in months
- `Credit_History`: Credit history meets guidelines (1: Good, 0: Bad)
- `Property_Area`: Urban / Semi-Urban / Rural
- `Loan_Status`: Target Variable (Y: Approved, N: Rejected)

## 🛠️ Tech Stack & Workflow
- **Language:** Python
- **Data Libraries:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn (Correlation Heatmap, Confusion Matrix)
- **Machine Learning:** Scikit-Learn
- **Algorithm Used:** Logistic Regression

## 📈 Key Insights & Results
- **Data Preprocessing:** Handled missing values in numerical and categorical columns, and performed proper label encoding.
- **Key Factor:** Credit History emerged as the most critical feature influencing loan approval.
- **Model Performance:** Built and evaluated a **Logistic Regression** model.
- **Evaluation Metrics:** Generated a detailed Classification Report and visualized the Confusion Matrix to check Precision, Recall, and F1-Score.

## 📂 Project Structure
- `loan_prediction.csv` - Raw historical dataset.
- `loan_dataset.ipynb` - Jupyter Notebook containing EDA, Data Preprocessing, Model Training, and Evaluation.
- `README.md` - Project documentation.

## 💻 How to Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/loan-approval-prediction.git](https://github.com/YOUR_USERNAME/loan-approval-prediction.git)
