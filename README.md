# Operationalizing-Machine-Learning

The Operationalizing Machine Learning project focuses on deploying and operationalizing a machine learning model using Microsoft Azure. The goal of this project is to showcase the end-to-end process of deploying a machine learning model as a REST API and creating a pipeline for automated model training and deployment.
This project involves several key components and steps. 

1. creating an Azure ML Workspace and configuring the necessary resources. 
2. train a machine learning model using Azure AutoML, which automates the process of model selection and hyperparameter tuning.
3. deploy it as a REST API endpoint using Azure Container Instances (ACI). This will allow you to interact with the model and make predictions using HTTP requests.
4.  enable Application Insights, which provides monitoring and logging capabilities. This will allow to track the performance and usage of the model endpoint.
5. create a pipeline using Azure ML SDK to automate the model training and deployment process. This pipeline will include the necessary steps to train the model, register it, and deploy it as a REST API endpoint.
6. create a screencast video demonstrating the entire process of deploying the machine learning model, including the working deployed model endpoint, the deployed pipeline, the available AutoML model, and successful API requests to the endpoint with a JSON payload.



## Architectural Diagram
The architecture diagram for this project showcases the flow of data and processes involved in deploying a cloud-based machine learning model using Azure. It illustrates the integration of various components such as Azure Machine Learning, AutoML, and Azure Pipelines to automate the model training, deployment, and consumption processes. The diagram also highlights the use of authentication, logging, and Swagger documentation to ensure security, monitoring, and easy access to the deployed model's endpoints.

![2screen-shot-2020-09-15-at-12 36 11-pm](Screenshots/screen-shot-2020-09-15-at-12.36.11-pm.png)

## Screenshot documentation
Brief documentation of each step and the outputs.

### Step 1: Authentication
I was using the lab Udacity provided, therefore i was able to skip this step.

### Step 2: Automated ML Experiment

In the Automated ML Experiment, an experiment is created and configured using Automated ML. Additionally, a compute cluster is set up to run the experiment and train a model using the bankmarketing_train.csv dataset.

![2023-06-22 (1)](Screenshots/2023-06-22%20(1).png)
![2023-06-22 (2)](Screenshots/2023-06-22%20(2).png)
![2023-06-22 (3)](Screenshots/2023-06-22%20(3).png)

### Step 3: Deploy the Best Model

In this step, we are able to interact with the HTTP API service and send data over POST requests to interact with the deployed model. After completing the previous automl experiment run, summary of all the models and their metrics can be found, including explanations. The best model is shown in the "Details" tab and is also be listed first in the "Models" tab for easy selection for deployment.

![2023-06-22 (11)](Screenshots/2023-06-22%20(11).png)

### Step 4: Enable Logging

To enable logging, configure the enable_logging parameter in the AutoMLConfig class to track and store logs of the experiment run.

![2023-06-22 (6)](Screenshots/2023-06-22%20(6).png)
![2023-06-22 (9)](Screenshots/2023-06-22%20(9).png)
![2023-06-22 (10)](Screenshots/2023-06-22%20(10).png)

### Step 5: Swagger Documentation

In the step "Swagger Documentation," a Swagger documentation for the deployed model's HTTP API is genereated. This documentation provides a detailed description of the API endpoints, input and output formats, and allows for easy testing and integration of the model into other applications.

![2023-06-16 (11)](Screenshots/2023-06-16%20(11).png)
![2023-06-16 (13)](Screenshots/2023-06-16%20(13).png)
![2023-06-16 (14)](Screenshots/2023-06-16%20(14).png)

### Step 6: Consume Model Endpoints
Once the model is deployed, the endpoint.py script provided is use to interact with the trained model. 

![2023-06-22 (12)](Screenshots/2023-06-22%20(12).png)

### Step 7: Create, Publish and Consume a Pipeline

To create, publish, and consume a pipeline in Azure Machine Learning, the Azure Machine Learning SDK is used in this step. First, pipeline steps is defined, configure the data and compute resources, and then the pipeline as a REST endpoint is published. Once published, the pipeline can be consumed by making HTTP requests to the endpoint, triggering its execution, and retrieving the results.

![2023-06-22 (13)](Screenshots/2023-06-22%20(13).png)
![2023-06-22 (21)](Screenshots/2023-06-22%20(21).png)
![2023-06-22 (17)](Screenshots/2023-06-22%20(17).png)
![2023-06-22 (18)](Screenshots/2023-06-22%20(18).png)
![2023-06-22 (19)](Screenshots/2023-06-22%20(19).png)
![2023-06-22 (20)](Screenshots/2023-06-22%20(20).png)
![2023-06-22 (15)](Screenshots/2023-06-22%20(15).png)


## Screen Recording
The screencast is provided in the .zip File.


