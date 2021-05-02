# Prediction-of-scores-using-Supervised-Learnig-ML
Problem Statement: Predict the percentage of student based on number of study hours.

SOLUTION: Linear Regression - It models target prediction value based on independent variables.

Hypothesis Function for simple linear regression: y = A + B.x, where y is the label of the data, x are input variables, A is intercept, B is slope.


Q - What will be predicted score if a student studies for 9.25 hrs/ day?


hours = 9.25
own_pred = regressor.predict([[9.25]])
print("No of Hours = {}".format(hours))
print("Predicted Score = {}".format(own_pred[0]))
No of Hours = 9.25
Predicted Score = 93.69173248737539
Evaluating the model
Mean square error:

from sklearn import metrics  
print('Mean Absolute Error:', 
      metrics.mean_absolute_error(y_test, y_pred))
Mean Absolute Error: 4.183859899002982
