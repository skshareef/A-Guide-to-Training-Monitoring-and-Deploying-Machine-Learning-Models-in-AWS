# A-Guide-to-Training-Monitoring-and-Deploying-Machine-Learning-Models-in-AWS

Detail guide  : https://medium.com/aws-tip/a-guide-to-training-monitoring-and-deploying-machine-learning-models-in-aws-51bf2a3347ab

## Summary of Steps for Machine Learning with Amazon SageMaker

1. **Introduction and Overview:**
   - Introduction to Amazon SageMaker as a cloud-based machine learning platform.
   - Overview of key services: AWS, Amazon SageMaker, and Amazon S3.

2. **Account Setup:**
   - Creation of an AWS account for accessing cloud services.

3. **IAM User Setup:**
   - Setting up IAM users for secure access to AWS resources.

4. **Amazon SageMaker Initialization:**
   - Launching Amazon SageMaker, a managed environment for machine learning.

5. **Data Preparation:**
   - Reshaping images and organizing files for image classification.
  
6. **Data Analysis and .lst Files Creation:**
   - Performing data analysis before creating .lst files.
   - Creating .lst files with image file information.

7. **Uploading Data to Amazon S3 Buckets:**
   - Creating an S3 bucket and uploading data and .lst files.

8. **Model Training:**
   - Initializing and setting hyperparameters for model training.
   - Utilizing pre-trained models or building custom models.
   - Training the model and tuning hyperparameters.

9. **Creating Model Endpoint:**
   - Creating an endpoint for the trained model for predictions.

10. **Lambda Function Creation:**
    - Establishing a Lambda function for serverless computing.

11. **API Creation with API Gateway:**
    - Creating an API using API Gateway for integrating with the Lambda function.

12. **Conclusion:**
    - Emphasizing best practices in data quality, monitoring, and security.
    - Encouraging experimentation and iterative learning with SageMaker.
