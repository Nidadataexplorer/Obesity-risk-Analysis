Obesity Level Predictor

This repository contains code for a machine learning model that predicts Obresity level outcomes based on various lifestyle factors. The model uses data related to individuals' habits, such as diet, exercise, technology usage, and transportation methods, to predict their obesity classification.

Dataset
The dataset used for training and testing the model is provided in the /data directory. It consists of two CSV files: train.csv and test.csv, containing training and test data, respectively.

Model Building

The model is built using Python and several libraries, including NumPy, pandas, scikit-learn, XGBoost, and Optuna. The following steps were performed in the model-building process:

1.	Data reading and cleaning: The dataset was loaded into pandas DataFrames, and missing values were handled appropriately.

2.	Exploratory data analysis (EDA): Various visualizations and analyses were conducted to understand the distribution and relationships among different features.

3.	Feature engineering: New features were created, and transformations were applied to existing features to improve model performance.

4.	Model selection and training: The XGBoost algorithm was chosen for its performance and scalability. Hyperparameter tuning was performed using Optuna to optimize model performance.

5.	Model evaluation: The model was evaluated on both training and test datasets using accuracy, precision, recall, and F1-score metrics.

Results
The trained model achieved the following performance metrics:
•	The model's accuracy on the training set is: 0.95
•	The model's accuracy on the test set is: 0.90
•	F1-score on the test set:
o	Class 1:  0.94 
o	Class 2:  0.88 
o	Class 3:  0.89
o	Class 4:  0.97
o	Class 5:  1.00
o	Class 6:  0.80
o	Class 7:  0.91
Feature importance analysis was also conducted to understand the factors contributing most to the model's predictions.
 

![image](https://github.com/Nidadataexplorer/Obesity-risk-ML-Model/assets/165329225/db424505-19df-442c-bd45-b6a6f6d7ab07)
