# Car-Insurance-Claim-Prediction
I built 4 machine learning models (Logistic Regression, Random Forest, Decision Trees and Gradient Boosting) and compared the predicting performance.
I chose the random forest model to predict whether the policyholder files a claim in the next 6 months or not. 

The dataset contains information on policyholders having the 43 attributes like policy tenure, etc, and the target variable. 
I did this project in the following steps:

(1) Implemented EDA using Pandas and NumPy, conducted feature engineering using Scikit-learn, performed imbalanced dataset treatment by introducing Imblearn.
(2) Split the data into training and testing set and feed them to the 4 ML models.
(3) Chose the random forest as the final model because it is powerful aand flexible, it also generate feature importance which can help optimize the model.
(4) I tested the model with a new dataset. The result indicated 2.3% customers will make claims and the car insurance company should be adjust their policies and procedures in order to accommodate the changing demand for claims.
