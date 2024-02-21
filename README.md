# Insurance-costs
This project focuses on estimating insurance costs using data from Kaggle. The objective is to develop a model for evaluating insurance costs. Dataset with description is in the following link https://www.kaggle.com/datasets/mirichoi0218/insurance

## Data Preprocessing
The data underwent cleaning and preprocessing to prepare for model development.

## Model Evaluation
Two regresion models were examined: Linear Regression and Random Forest Regression.

## Linear Regression Model
The linear regression model showed not very good performance metrics on the test data:

R2 score is : 71%
Mean Absolute error: 4.300
Mean value : 13.079
Very wide margins up and down from real value, which leads to low accuracy

## Random Forest Model
The Random Forest model demonstrated better results.

R2 score is : 85%
Mean Absolute error : 2.439
Which leads to have almost halg of margins thus better accuracy.


## Conclusion
 Random Forest model outperforming the Linear Regression model with better accuracy. The average percentange error is 18,64%. For example when the real charge is 10.000, the prediction is between 
8.154 and 11.864, which seems acceptable.
