# Diabetes-Prediction
This project aims to develop a Grammatical Evolution (GE) model for binary classification on the Diabetes dataset, with the objective of predicting whether an individual in the dataset has diabetes or not. 

# Data Exploration
The Diabetes dataset used for this project is a modified version with a selected subset of features from the original data. However, it still includes essential attributes related to health metrics, lifestyle factors, and demographic information.

The dataset features a range of health and demographic indicators: 
Boolean Features like High Blood Pressure, High Cholesterol, Smoker, Stroke, Cholesterol Check, Heart Disease or Attack, Physical Activity, Fruits, Vegetables, Alcohol Consumption, Health care and certain other features.
Non - Boolean Features such as BMI, Mental Health, Physical Health, General Health, Age, Education and Income

# Data Exploration
There are various scaling techniques, such as Standard Scaler and MinMax Scaler, that transform data to a specific range to improve model performance. In this case, Standard Scaler appeared to perform well with the data. So, we have proceeded with the Standard Scaler as our scaling mechanism.

# Results
We received a training accuracy of 74.4% with the test accuracy of 69.02%
