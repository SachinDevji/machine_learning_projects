Insurance Cost Prediction using Linear Regression
Project Overview
This project predicts insurance charges based on customer information such as age, gender, BMI, number of children, smoking habits, and region using Machine Learning techniques. The goal is to build a regression model that can estimate medical insurance costs accurately.
________________________________________
Problem Statement
Insurance companies need to estimate healthcare expenses for customers. This project uses historical insurance data to predict future insurance charges and identify the factors that most influence insurance costs.
________________________________________
Dataset Description
Features
•	age – Age of the customer
•	sex – Gender of the customer
•	bmi – Body Mass Index
•	children – Number of dependent children
•	smoker – Smoking status
•	region – Residential region
Target Variable
•	charges – Medical insurance cost
________________________________________
Technologies Used
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Scikit-Learn
•	Jupyter Notebook
________________________________________
Project Workflow
1. Data Collection
•	Loaded insurance dataset into a Pandas DataFrame.
2. Data Preprocessing
•	Checked missing values.
•	Removed duplicates.
•	Handled categorical variables using encoding techniques.
•	Prepared features and target variables.
3. Exploratory Data Analysis (EDA)
•	Statistical summary of data.
•	Correlation analysis.
•	Distribution plots.
•	Relationship between features and insurance charges.
4. Feature Engineering
•	Converted categorical features into numerical format.
•	Selected relevant features for model training.
5. Model Building
•	Applied Linear Regression.
•	Split dataset into training and testing sets.
6. Model Evaluation
•	Mean Absolute Error (MAE)
•	Mean Squared Error (MSE)
•	Root Mean Squared Error (RMSE)
•	R² Score
________________________________________
Results
Metric	Value
Adjusted R^2	79.87
R² Score	80.40
(Replace with your actual results.)
________________________________________

Future Improvements
•	Hyperparameter tuning
•	Feature selection techniques
•	Comparison with Random Forest Regressor
•	Deployment using Flask/Streamlit
________________________________________
Author
Sachin Devoji
GitHub: https://github.com/SachinDevji

