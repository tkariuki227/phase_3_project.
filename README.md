 ## SyriaTel Customer Churn Prediction
## Project Overview
This project explores customer churn (when customers leave a service) for SyriaTel, a telecommunications company. The goal was to build a machine learning model that can predict which customers are likely to churn, so that the company can take preventive action.
________________________________________
 Dataset
The dataset was provided as part of the course and includes over 3,000 customer records with the following details:
•	Usage statistics (day, evening, night, international)
•	Service plans (international plan, voicemail plan)
•	Customer service calls
•	Whether the customer churned or not
________________________________________
 Data Cleaning
•	Dropped irrelevant columns (like state and phone number).
•	Handled missing values and checked for duplicates.
•	Converted categorical data (like "yes"/"no") to numeric values.
•	Scaled numerical features for better model performance.
•	Balanced the dataset to handle class imbalance (more non-churners than churners).
________________________________________
Models Used
1. Logistic Regression
•	A simple, interpretable model.
•	Accuracy: ~86%
•	Helped understand which features influence churn.
2. Decision Tree Classifier
•	More flexible and accurate model.
•	Accuracy: ~91%
•	Performed better at identifying churners.
________________________________________
Key Insights
•	Customers with international plans and those who made many service calls were more likely to churn.
•	Having a voicemail plan or higher voicemail message counts were linked to loyalty.
•	High daytime usage also appeared in many churn cases.
________________________________________
 Visualizations
•	Confusion matrices to show model predictions.
•	ROC curve to measure model performance.
•	Bar charts showing most important features.
•	Target variable distribution (churn vs. no churn).
________________________________________
Conclusion
The Decision Tree model outperformed Logistic Regression and is recommended for deployment. It helps identify at-risk customers with high accuracy, offering SyriaTel the opportunity to retain customers through better service or targeted offers.
________________________________________
 How to Run the Project
1.	Open the Jupyter Notebook (SyriaTel_Churn_Prediction.ipynb)
2.	Run the cells step by step (you need Python, pandas, scikit-learn, matplotlib, seaborn)
3.	You’ll see the cleaning steps, model training, evaluations, and visualizations
________________________________________
Author
•	Name: [Teresia Kariuki]
•	Course: Machine Learning Fundamentals
•	Instructor: [Brian Chacha]
•	Date: [9.05.2025]

