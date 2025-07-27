# Customer-Churn-Prediction

## Project Overview
This project aims to predict customer churn for a telecom company based on various factors such as demographics, services availed, and financial details. The dataset contains information about customer behavior, including contract type, internet service, and monthly charges. By applying **Exploratory Data Analysis (EDA)** and **Machine Learning models**, we can gain insights into churn patterns and improve customer retention strategies.

## Features
- **Exploratory Data Analysis (EDA)**: Visualization and insights into customer behavior.
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Hyperparameter Tuning**: Using optuna to perform hyperparameter tuning for logistic regression.
- **Predictive Modeling**: Using Logistic Regression Machine Learning model.
- **Model Evaluation**: Performance metrics including accuracy_score, confusion matrix, and k-fold cross validation. 
- **Feature Importance Analysis**: Identifying key factors influencing churn.

## Technologies Used
- **Python**
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/JPS9380/Customer-Churn-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Customer-Churn-Prediction
   ```
3. Create a virtual python environment
   ```bash
   python3 -m venv venv
  ```
4. Activate the virtual environment
   ```bash
   source venv/Scripts/Activate #on windows
   source venv/bin/activate #on linux
  ```
5. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The dataset consists of **7,043 records** and **21 columns**, including customer demographic information, services used, and financial details.

- **Target Variable**: `Churn` (Yes/No) - Whether a customer left the service.
- **Key Features**:
  - `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - `InternetService`, `OnlineSecurity`, `TechSupport`
  - `Contract`, `PaperlessBilling`, `PaymentMethod`
  - `MonthlyCharges`, `TotalCharges`
  - `tenure` (Number of months a customer has stayed with the company)

## License
This project is licensed under the MIT License.

