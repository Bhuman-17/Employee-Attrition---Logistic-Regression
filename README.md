# 🧠 Employee Attrition Prediction App

This project is a **Streamlit web application** that predicts whether an employee is likely to leave the company (attrition) based on various HR-related features such as age, job role, satisfaction levels, overtime, and more. The model is built using a trained `attrition_model.joblib` file.

---

## 🚀 Features

- Interactive UI to input employee details
- Predicts **Attrition: Yes or No**
- Utilises a **trained machine learning model**
- User-friendly sliders, dropdowns, and numeric inputs
- Preprocessing and prediction handled seamlessly

---

## 🧾 Input Features

The model accepts the following inputs:

- Age, DistanceFromHome, Gender, OverTime  
- BusinessTravel, Department, EducationField, JobRole, MaritalStatus  
- DailyRate, HourlyRate, MonthlyIncome, MonthlyRate  
- EnvironmentSatisfaction, JobSatisfaction, RelationshipSatisfaction  
- JobInvolvement, JobLevel, PerformanceRating  
- StockOptionLevel, TrainingTimesLastYear, TotalWorkingYears  
- WorkLifeBalance, YearsAtCompany, YearsInCurrentRole  
- YearsSinceLastPromotion, YearsWithCurrManager  

_Categorical inputs are handled appropriately within the model pipeline._

---

## ⚙️ How to Run

1. **Clone the repository**
git clone https://github.com/yourusername/employee-attrition-app.git
cd employee-attrition-app
Install dependencies

pip install -r requirements.txt
Run the Streamlit app

streamlit run app.py

## 🗃️ Files Included
File	Description
app.py	Main Streamlit app script
attrition_model.joblib	Trained ML model using scikit-learn
requirements.txt	Python dependencies
README.md	Project documentation

## 💡 Model Info
Model Type: Trained using scikit-learn (e.g. Logistic Regression)

Saved as: attrition_model.joblib

Output: Yes (Will Leave) or No (Will Stay)

## 🙌 Credits
Built with ❤️ using:
Python
Streamlit
Pandas
scikit-learn
Joblib

## streamlit app link :  https://bhuman-17-employee-attrition---logistic-regression-app-omk6ng.streamlit.app/
