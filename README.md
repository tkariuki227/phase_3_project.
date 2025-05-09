# phase_3_project.
This project aims to predict customer churn for SyriaTel, a telecom company. By identifying these customers early, the company can take action to keep them.
SyriaTel Customer Churn Prediction 
 Data Preparation
We started with a dataset containing information about over 3,000 customers, including details like:
•	Whether they have an international plan
•	How many minutes they use during the day, evening, and night
•	How often they call customer service
•	Whether they have a voicemail plan
Steps taken:
•	Cleaned the data by removing irrelevant columns and checking for missing values or duplicates.
•	Converted all the data into a suitable format for machine learning (like changing “yes”/“no” to 1/0).
•	Scaled the data to make the values more comparable.
•	Balanced the dataset to fix the issue of having more non-churners than churners.
________________________________________
Model Building
We trained two models to predict churn:
1.	Logistic Regression (basic model we studied in class):
o	Accuracy: 86%
o	Predicted most non-churners well.
o	Struggled a bit with correctly identifying customers who actually left.
o	Still gave useful insights into important factors.
2.	Decision Tree (extra model for comparison):
o	Accuracy: 91%
o	Performed better at catching both churners and non-churners.
o	Easier to interpret visually (we can see decision paths).
o	Slightly more complex than Logistic Regression.
________________________________________
Key Insights
The most important factors linked to churn:
•	Having an international plan increases the chance of leaving.
•	Frequent customer service calls is a strong sign of dissatisfaction.
•	Customers with no voicemail plan or low voicemail usage were more likely to churn.
•	High day-time usage was also linked to higher churn.
________________________________________
Visual Results
We used visual charts to show:
•	How the model makes decisions.
•	Which features matter the most.
•	How well the model distinguishes between churners and non-churners.
These visuals make it easier for anyone to understand the patterns in customer behavior.
________________________________________
Conclusion & Recommendation
Our Logistic Regression model gave a strong baseline, but the Decision Tree performed better overall, especially at identifying customers who are at risk of leaving.
We recommend:
•	Monitoring customers with international plans and high service calls.
•	Using this model to flag at-risk customers early so SyriaTel can offer promotions or improved service.
•	Continuing to improve the model with more data over time.
