# maternal-health-complications

Imagine this scenario: a patient walks into the ER, and you would like to see the probability of the patient having a maternal health complication and needs immediate attention or special care.

logistic_reg_mhc.ipynb consists of code training a Logistic Regression model to predict when a patient has a maternal health complication. 
knn_mhc consists of code training a K-nearest neighbor model to predict when a patient has a maternal health complication. 

Test recall scores reached 91%, which means that in 9/10 cases where a woman walked into the ER, they were correctly identified as having a maternal health complication.
Future work: test precision scores were very low (below 20%). There were many false negatives in the results, which may be the next area of focus. 
