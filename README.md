# Sagemaker XGBoost Implementation for predicting Bank Customer Behavior

In this mini-project we used a sample dataset provided by AWS, which contains 60 columns of data about approximately 41,000 bank customers, and whether or not they enrolled for a particular bank product.

The objective was to use AWS Sagemaker to create an XGBoost Model which can predict whether customers enrolled for the bank product.

### Model Performance


 
### Learnings from Project

The primary learnings from this project included:
- creation of XGBoost model using AWS container and EC2 instances including evaluation of instant types (memory- vs compute-bound)
- storage and uploading of inputs and outputs in S3
- creation of model endpoint which can be used for prediction purposes

Using the boto3 SDK, model development, deployment etc with AWS seems pretty straightforward. What was surprising to me is the amount of time required for starting / stopping notebook instances and starting model training. On the other hand, model training can of course be completed much faster due to the additional compute power.
