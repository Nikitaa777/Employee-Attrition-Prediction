# Employee Attrition Prediction

## 📌 Project Overview
This project analyzes an employee dataset to understand the factors influencing **employee attrition** and builds predictive models to forecast whether an employee is likely to leave.  

The notebook includes data preprocessing, exploratory data analysis (EDA), and machine learning model training with evaluation.

## 📂 Dataset
- **File:** `aug_train.csv`  
- **Columns include:** demographic details, education, job role, work environment, etc.  
- **Target Variable:** `Attrition` (Yes/No)  

### Data Preprocessing
- Checked and handled **missing values**  
- Encoded **categorical features**  
- Defined **features (X) and target (y)**  

## 🔎 Exploratory Data Analysis (EDA)
- Attrition by gender  
- Attrition distribution across categories (education, job role, etc.)  
- Visualizations for better insights  

## 🤖 Machine Learning
### Steps:
1. Split dataset into training & test sets  
2. Train multiple machine learning models  
3. Compare model accuracy  

### Models Used:
- Logistic Regression  
- Random Forest  
- Decision Tree  
- Other classifiers  

## 📊 Results
- Accuracy comparison plotted across models  
- Insights into key attrition factors from EDA  

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone <your-repo-link>
   cd employee-attrition
