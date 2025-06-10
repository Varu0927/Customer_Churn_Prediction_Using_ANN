Customer Churn Prediction
This project builds a Customer Churn Prediction Model using a Neural Network.The model identifies customers likely to churn (leave the service), helping businesses take proactive retention actions.

Project Files
Customer_Churn_prediction.ipynb - Jupyter notebook with full code (EDA + Neural Network + Evaluation)
Churn_Modelling.csv - Dataset used



Problem Statement
Customer churn refers to the percentage of customers that stop using a company's product or service during a certain time frame.Reducing churn rate is critical to improve customer lifetime value and maintain stable revenue streams.

Project Goal
Build a Neural Network model to classify whether a customer will churn or stay.
Analyze key drivers of churn.
Provide business insights to reduce churn.

Tools and Libraries Used
Python
Pandas - Data manipulation
NumPy - Numerical operations
Matplotlib / Seaborn - Visualization
TensorFlow / Keras - Neural Network model
Jupyter Notebook

Machine Learning Workflow
Data Loading and Exploration
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Churn distribution
Churn vs Gender
Age distribution

Model Building
Neural Network (Keras Sequential Model)

Model Evaluation
Accuracy=86%


Dataset
Source: Churn_Modelling.csv
Rows: 10,000+
Features include:
Customer demographics (Age, Gender, Geography)
Account information (CreditScore, Balance, Tenure, NumOfProducts)
Customer engagement (HasCrCard, IsActiveMember)
EstimatedSalary
Target - Exited (1 = churned, 0 = stayed)

Results
Neural Network model trained and evaluated successfully.
Achieved an accuracy of approximately XX percent on test data.
Top drivers of churn observed in the data include:
Age
Geography
IsActiveMember

Business Impact
Helps identify high-risk customers.
Enables targeted retention campaigns.
Provides insights on churn drivers for improving services.
