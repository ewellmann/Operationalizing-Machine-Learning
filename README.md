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

<img width="626" alt="screen-shot-2020-09-15-at-12 36 11-pm" src="https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/0bbea764-8936-4103-b497-3d4a6ee700c6">

## Screenshot documentation
Brief documentation of each step and the outputs.

### Step 1: Authentication
I was using the lab Udacity provided, therefore i was able to skip this step.

### Step 2: Automated ML Experiment
![2023-06-22 (1)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/23bbccc9-9221-4153-ad5f-12b5edc566fa)
![2023-06-22 (2)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/09754b8e-6507-437e-8e91-c7168152595e)
![2023-06-22 (3)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/f13814c5-4bc6-463f-847c-52d3510c5af6)

### Step 3: Deploy the Best Model
![2023-06-22 (11)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/4bba5f00-7445-438f-a36d-29613aa956b8)

### Step 4: Enable Logging
![2023-06-22 (6)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/f0af444f-f538-48dd-ba4e-ec8442a89ece)
![2023-06-22 (9)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/c8c3dc71-3698-4235-8387-3032457259fb)
![2023-06-22 (10)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/7ab264a5-340b-4a5d-a6fd-224c5a75871d)

### Step 5: Swagger Documentation
![2023-06-16 (11)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/fd00772f-8f41-41cd-af63-32f616f90ec2)
![2023-06-16 (13)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/e8ed7681-bbb7-4030-b983-3739a23381f3)
![2023-06-16 (14)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/c29c8a63-614f-4fff-9c1b-57539c53a862)

### Step 6: Consume Model Endpoints
![2023-06-22 (12)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/c02f654f-39d1-476d-b320-67d792c5958f)

### Step 7: Create, Publish and Consume a Pipeline
![2023-06-22 (13)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/6b87cc40-65c6-49c7-b67a-b483d6ef2936)
![2023-06-22 (17)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/f6d1912c-6d1a-4fdf-a2bd-71b27df0a2a7)
![2023-06-22 (18)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/8b395a64-9406-452c-bdc7-3a57937a25ca)
![2023-06-22 (21)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/ba6dc349-627f-4a4c-8d1b-f6113b24467f)
![2023-06-22 (19)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/ab860655-aec9-4e2c-81cf-c5e1ffe2ee5e)
![2023-06-22 (20)](https://github.com/ewellmann/Operationalizing-Machine-Learning/assets/59996314/f677ed43-89ed-4ac8-b715-717fd2ace09b)


## Screen Recording
The screencast is provided in the .zip File.


