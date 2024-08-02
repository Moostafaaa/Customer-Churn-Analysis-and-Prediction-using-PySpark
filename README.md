# Customer-Churn-Analysis-and-Prediction(99.07%)-using-PySpark

## Project Objective
To develop a machine learning model using PySpark to predict customer churn within a telecommunications company. By analyzing customer data, the model will identify key factors contributing to churn and provide actionable insights to improve customer retention.

## Data Description
The dataset contains customer-level information with each row representing a unique customer and each column representing a customer attribute. Key attributes include:

* Customer demographics: gender, age range, partner, dependents
* Customer behavior: services subscribed (phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV and movies), tenure, contract type, payment method, paperless billing, monthly charges, total charges
* Target variable: Churn (whether the customer left within the last month)
  
## Project Workflow
The project involves the following key steps:

* Data Loading: Import the dataset into a PySpark DataFrame.
* Exploratory Data Analysis (EDA): Understand data characteristics, identify missing values, outliers, and correlations between variables.
* Data Preprocessing: Handle missing values, outliers, and inconsistencies. Convert categorical data into numerical format (e.g., one-hot encoding).
* Feature Engineering: Create new features or transform existing ones to improve model performance.
* Data Splitting: Divide the dataset into training and testing sets.
* Model Training: Build a machine learning model (e.g., Logistic Regression, Random Forest, Gradient Boosting) using PySpark's MLlib.
* Model Evaluation: Assess the model's performance using metrics like accuracy and AUC-ROC.
* Model Monitoring: Continuously monitor the model's performance and make adjustments and trying new feature engineering
* Resampling for model optimization
* Model Deployment: Deploy the model coefficients to gain insights and make recommendation to stakeholders.
