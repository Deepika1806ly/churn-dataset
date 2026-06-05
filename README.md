Customer Churn Analysis Using Python
Project Description
This project is a Customer Churn Analysis System developed using Python.
The project generates a large synthetic customer dataset and performs data analysis to identify customers who are likely to leave the company (churn).
Using data preprocessing, statistical analysis, and visualizations, the project helps understand customer behavior and factors affecting churn.
Objectives
Generate customer dataset using Python
Analyze customer churn behavior
Perform data preprocessing
Create visual reports using graphs
Identify important churn factors
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Libraries Used
Python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
Dataset Information
The dataset contains 100000 customer records with the following attributes:
Column Name
Description
Customer_ID
Unique customer ID
Age
Age of customer
Gender
Male or Female
Tenure
Number of years with company
Balance
Customer account balance
CreditScore
Credit score
EstimatedSalary
Estimated annual salary
NumOfProducts
Number of products used
IsActiveMember
Active membership status
Churn
Customer churn status
Churn Conditions
A customer is marked as churn if:
Balance is less than 50000 and customer is inactive
Credit score is below 400 and tenure is less than 3
Customer uses only one product and is inactive
If conditions are satisfied:
Churn = 1
Otherwise:
Churn = 0
Project Workflow
1. Import Libraries
Required Python libraries are imported.
2. Generate Dataset
Random customer data is created using NumPy.
3. Create Churn Logic
Customer churn conditions are applied.
4. Save Dataset
Dataset is saved as:
Python
customer_churn_data.csv
5. Data Preprocessing
Check missing values
Remove null values
Convert categorical values into numeric format
6. Statistical Analysis
Summary statistics are generated using:
Python
data.describe()
7. Data Visualization
Graphs are generated to analyze:
Age distribution
Churn percentage
Balance vs churn
Credit score distribution
Correlation between variables
8. Churn Customer Extraction
Customers with churn status = 1 are identified.
Visualizations Included
Histogram
Bar Chart
Pie Chart
Scatter Plot
Box Plot
Heatmap
Key Findings
Inactive customers have high churn rate
Customers with only one product churn more
Low credit score customers are more likely to churn
Balance and activity status strongly affect churn
Output
The project produces:
CSV dataset file
Statistical summaries
Graphical visualizations
Churn customer analysis
Advantages
Easy to understand
Useful for beginner data science projects
Demonstrates customer behavior analysis
Helps in business decision making
Future Enhancements
Add Machine Learning models
Predict churn using classification algorithms
Create dashboard using Streamlit
Use real banking/customer datasets
Improve churn prediction accuracy
Conclusion
This project successfully demonstrates customer churn analysis using Python libraries.
It helps identify important customer patterns and provides insights into customer retention strategies.
Author
Mini Project developed using Python for Data Science and Customer Analytics.
