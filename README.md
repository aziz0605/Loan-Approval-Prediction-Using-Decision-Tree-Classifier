# 🏦 Loan Approval Prediction Using Decision Tree Classifier

## 📌 Project Overview

This project focuses on predicting whether a loan application will be approved or rejected using Machine Learning techniques.

A Decision Tree Classifier is used to analyze applicant information such as income, education, credit history, marital status, loan amount, and property area to predict loan approval status.

The project also includes data preprocessing, Exploratory Data Analysis (EDA), model training, evaluation, and visualization.

## 🎯 Objectives

- Analyze loan applicant data.
- Handle missing values and clean the dataset.
- Perform Exploratory Data Analysis (EDA).
- Build a Decision Tree Classification model.
- Evaluate model performance.
- Identify important features influencing loan approval.
- Predict loan approval status for new applicants.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📂 Project Structure

```text
Loan-Approval-Prediction/
│
├── LOAN_PREDICTION_DATA_ANALYSIS.ipynb
├── loan_prediction_train.csv
├── decision_tree.png
└── README.md
```

## 📊 Dataset Description

The project uses a loan prediction training dataset containing applicant details.

Important features include:

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

**Target Variable:** Loan_Status

- Y – Loan Approved
- N – Loan Rejected

## ⚙️ Project Workflow

### 1. Data Loading
Load the loan prediction dataset using Pandas.

### 2. Data Preprocessing
- Remove unnecessary Loan_ID column.
- Handle missing categorical values using mode.
- Handle missing numerical values using median.
- Convert categorical features into numerical values using LabelEncoder.

### 3. Exploratory Data Analysis (EDA)

Perform data analysis and visualize:

- Loan Status Distribution
- Gender vs Loan Status
- Education vs Loan Status
- Credit History vs Loan Status

### 4. Model Building

Build a Decision Tree Classifier using Scikit-learn.

Model Configuration:

- Algorithm: Decision Tree Classifier
- Criterion: Gini
- Max Depth: 5
- Random State: 42

### 5. Model Evaluation

Evaluate the trained model using:

- Accuracy Score
- Classification Report
- Precision
- Recall
- F1-Score

The dataset is split into 80% training data and 20% testing data.

### 6. Feature Importance

Analyze the importance of different features to understand which factors influence loan approval predictions.

### 7. Prediction

Use the trained model to predict loan approval status for a new applicant.

## 📈 Visualizations

The project includes:
- Loan Status Distribution Chart
- Gender vs Loan Status
- Education vs Loan Status
- Credit History vs Loan Status
- Decision Tree Visualization
- Feature Importance Chart

## 🚀 How to Run This Project

**Step 1:** Clone this repository.

```bash
git clone https://github.com/your-username/Loan-Approval-Prediction.git
```

**Step 2:** Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**Step 3:** Place the dataset `loan_prediction_train.csv` in the appropriate location.

**Step 4:** Open the Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open `LOAN_PREDICTION_DATA_ANALYSIS.ipynb` and run all cells.

## 🎓 Learning Outcomes

- Understanding data preprocessing techniques.
- Performing Exploratory Data Analysis.
- Implementing Decision Tree Classification.
- Evaluating Machine Learning models.
- Understanding feature importance.
- Making predictions using trained models.

## 👨‍💻 Author

**Mohamed Aziz**

## ⭐ Conclusion

This project demonstrates how Machine Learning can be applied to loan approval prediction using a Decision Tree Classifier. It helps understand the relationship between applicant details and loan approval outcomes through data analysis and predictive modeling.
