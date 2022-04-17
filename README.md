
# Thyroid Disease Detection

Thyroid disease is a common cause of medical diagnosis and prediction, with an onset that is difficult to forecast in medical research. The thyroid gland is one of our body's most vital organs. Thyroid hormone releases are responsible for metabolic regulation. Hyperthyroidism and hypothyroidism are one of the two common diseases of the thyroid that releases thyroid hormones in regulating the rate of body's metabolism.



## Acknowledgements
Dataset URL:https://archive.ics.uci.edu/ml/machine-learning-databases/thyroid-disease/thyroid0387.data
Image URL:https://griefprobatejourneyhome.files.wordpress.com/2021/01/january-a-month-dedicated-to-thyroid-1-1.jpg?w=611

## Problem Statement

The main goal is to predict the estimated risk on a patient's chance of obtaining thyroid disease or not.




## Authors

- Kaushiki(kaushiki.bhardwaj10@gmail.com)


## Deployment
The solution is deployed on Amazon Web Services (AWS) on EC2 Instance using Ubuntu environment.


## Data Transformation
•	Removing of outliers
•	Deletion of unnecessary features
•	Imputation of null values
•	Feature Selection
•	Re-scaling the data into a range of 0 and 1 
•	Fixing the imbalanced data

## Model Training
After data processing, data is sampled into training, testing and validation. Then training data is fitted into 6 different models and they are tested on testing data. Finally, two best models are selected based on performance metrics.
## Model Selection
Training data is used to train multiple models. Two models were selected based on performance metrics. They are Random Forest and XGBoost.
## Prediction
The validation data is used as a final test for our models. The output of both the models is ensembled and the final values are tested. 
## Features

•	Reducing human error
•	Efficiency in detecting disease
•	24*7 working model

## Use Cases
•	Click the link and enter the homepage
•	Enter the patient details (TSH, T4U, FTI and TT4)
•	Hit the predict button
•	Get to know if you are thyroid free or not.

