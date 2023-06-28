# AWS-Sagemaker-Bank-Customer-Predictions

## Business Understanding:

The aim of this project is to identify potential customers for a bank who are likely to subscribe to the bank's services. This is achieved through a binary classification task using AWS SageMaker, Hyperparameter Tuning, Amazon S3, and other AWS cloud services. The classification is performed using the Sagemaker inbuilt XGBoost model, a popular machine learning algorithm for binary classification problems.

## Results:
The project's outcome is a trained machine learning model that can accurately predict the likelihood of a customer subscribing to the bank's services based on their independent features. The model can be integrated into the bank's system to automate the process of identifying potential customers and improving the overall efficiency of the bank's marketing strategies.

## Technologies used:

### Cloud Services
1. Amazon SageMaker
2. Amazon S3
3. Amazon IAM Role
4. SageMaker Hyperparameter Tuning

### Programming language: 
1. Python

## Approach:

The project involves several stages, starting with data collection, cleaning, and preprocessing. The preprocessed data is then used to train the XGBoost model using SageMaker. Hyperparameter tuning is performed to optimize the model's performance, and the final model is then deployed for inference. The use of various AWS cloud services ensures efficient data storage, processing, and model training. Amazon S3 is used for storing the input data, while SageMaker is used to train the model and perform hyperparameter tuning, resulting in an optimized model for maximum accuracy and performance.
