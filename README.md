# maternal-health-complications

For healthcare workers worldwide, ensuring that expectant mothers receive the necessary care is essential, especially when they encounter maternal health complications.

We trained a logistic regression model, knn model, XGBoost model and multilayer perceptron model to take past medical data, demographics, and information about hospital walk-ins and predict if the patient had a maternal health complication. The code for logistic regression and knn is included in this repository.

Test recall scores reached 91%, which means that in 9/10 cases, a woman with a maternal health complication from our dataset was correctly identified as having the complication.

Future work would fall on test precision metrics (scored below 20%). There were many false negatives in the results, which may be the next area of focus. 

Overally accuracy reached 80%.
