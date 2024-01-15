
# Employee Retention Machine Learning model

Built an auto machine Learning model trained on previous data that can predict Employees that can leave.

## Problem Statement

We are having issues with keeping employees so we would like a data analyst to help to proactively find employees that are at risk of quitting.
## Analysis Questions

1] What is causing employees to leave?

2] Who is predicted to leave?

3] Are employees satisfied?

4] Which departments have the most churn?

5] What trends are important?
## Approach

1] Building a database in Bigquery.

2] Connect to database with Python libraries(Google colab to Big Query).

3] Build a churn model(pycaret)

4]Export data to Bigquery

5]Build a dashboard using google looker studio.
## Machine learning Workflow

1] Train - Train Machine learning model on 70% of our existing 15000 employees.

2] Test - Test and Tune the machine learning model for accuracy on remaining 30%.

3] Predict - Use the optimized Machine Learning model to predict which employees in our pilot will churn.