# maternal-health-complications

Imagine this scenario: a woman walks into the ER, and you would like to see the probability of the patient having a maternal health complication and needs immediate attention or special care.

We trained a logistic regression model, knn model, XGBoost model and multilayer perceptron model to take past medical data, demographics, and information about the walk-in and predict if the patient had a maternal health complication. The code for logistic regression and knn is included in this repository.

Test recall scores reached 91%, which means that in 9/10 cases where a woman who had a maternal health complication walked into the ER, they were correctly identified as having the complication.
Future work: test precision scores were very low (below 20%). There were many false negatives in the results, which may be the next area of focus. 
Overally accuracy reached 80%.
