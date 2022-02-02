# CovidcasePrediction
A machine learning model for Covid case prediction


Problem Statement
  Using regression algorithms we can able to track the active covid cases
  

Problem oppertunity
  We need to get data. We'll use a sample data set for that. The raw data is completely infused in the workspace. Preprocessing is done before the analyzing part. The data must be clean so that the model can analyze correctly. For that the rows with empty values are removed. A module is added fothat process. Individual measurable properties are called features. Each row is representing an automobile and each column represents the feature of that automobile. The model is build accordingly. Now that the data is ready, constructing a predictive model consists of training and testing. We'll use our data to train the model, and then we'll test the model to see how closely it's able to predict prices. Because we want to predict no of cases, which is a number, we'll use a regression algorithm.
  
  Azure Machine learning studio
  
  Here we are using 2 Algorithms 
  1. Linear Regression
  2. Neural Network Regression
  
  ![image](https://user-images.githubusercontent.com/83619179/152097856-4cdf981d-7e67-4af8-beab-653dd9c741a1.png)
  
  ![image](https://user-images.githubusercontent.com/83619179/152098164-f1240a2b-5c6b-4eb5-b0a6-946c17159361.png)

![image](https://user-images.githubusercontent.com/83619179/152098560-d6605723-3f91-4020-ae41-9cbfdc54e6da.png)

1. The input values are to be found
2. The csv file is converted to dataset
3. The data miss is cleaned 
4. Split data
5. The regression algorithms Linear Regression and Neural Network Regression takes place
6. The data is trained
7. Train model
8. Score model 
9. Evaluate Model
10. Output values obtained

In this case the both the training experiment and predicive experiments are done.

The API key: 8Lnx6+i4W7R2i7aFyGh+gmbhrnEpHrdFzd84kmvka7yEKTnt8P8EEKK46oXxmHHQphffTh9FvdPA2g3FEpCkgw==

https://studio.azureml.net/Home/ViewWorkspaceCached/5343e8d2284d47de9d5a3c941a85e8bf#Workspaces/Experiments/Experiment/5343e8d2284d47de9d5a3c941a85e8bf.f-id.06f7bb2e287e4d74aeaaf2223be0b151/ViewExperiment

The data prediction part is done as

1. Cough
2. Fever
3. Sore Throat
4. Shortness of Breath
5. Headache
6. Age 60 or Above
7. Corona Result

By giving these values as sample we can predict.

https://studio.azureml.net/Home/ViewWorkspaceCached/5343e8d2284d47de9d5a3c941a85e8bf#Workspaces/Projects/Project/66450ebc-1dd6-44c3-a580-808dfc470798/ProjectDetails
![image](https://user-images.githubusercontent.com/83619179/152099769-72e2cbec-d6ba-4b1b-8a23-fc7f9777a34d.png)

After that Deploy web service part is done the project is published to gallery. 
https://gallery.cortanaintelligence.com/Experiment/Covid-19-prediction-two-algos-Predictive-Exp



