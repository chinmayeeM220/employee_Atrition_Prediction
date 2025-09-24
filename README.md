# employee_Atrition_Prediction


##  Project Overview
This project predicts whether an employee is likely to leave a company using **machine learning models**. By analyzing factors like **job satisfaction, salary, work environment, experience, and demographics**, organizations can proactively reduce attrition and improve retention.

##  Features
- Predicts employee attrition risk (Yes/No).
- Analyzes multiple influencing factors:
  - Job satisfaction
  - Work-life balance
  - Compensation and benefits
  - Years at company and experience
  - Department, role, and other demographics
- Visualizes important features and patterns in data.
- ROC Curve analysis to evaluate model performance.

## 🗂 Dataset
- Dataset: IBM HR Analytics Employee Attrition Dataset (available on Kaggle)
- Includes employee information such as age, gender, department, job role, salary, tenure, performance, satisfaction, etc.
- Preprocessing steps:
  - Handling missing values
  - Encoding categorical variables
  - Standardization of numeric features
  - Dropping irrelevant columns like EmployeeNumber, Over18, StandardHours

##  Technologies & Tools
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning Models:** Logistic Regression, Decision Tree, Random Forest  

##  Project Workflow
1. Import libraries and load dataset.
2. Data exploration and visualization.
3. Preprocess data (encoding, scaling, dropping irrelevant columns).
4. Train-test split.
5. Build and train machine learning models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
6. Evaluate models using accuracy, classification report, confusion matrix, ROC curve.
7. Analyze feature importance to understand critical factors affecting attrition.

##  Outcome
- Identifies employees at high risk of leaving.
- Supports HR teams in making **data-driven decisions**.
- Highlights key factors affecting employee retention for strategic planning.


