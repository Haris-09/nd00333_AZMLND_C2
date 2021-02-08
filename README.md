


# Operationalizing Machine Learning

This is the second project of Machine Learning Engineer with Microsoft Azure Nanodegree. In this project we used the bankmarketing dataset to predict wheter the customer will subscribe to fixed-term deposit or not. Which means this is a Binary Classification problem.

In this project we create, publish and consume the pipeline. The project starts with authenticating to Azure Machine Learning services, then we created an AutoML Experiment, then we deployed the best model, then we enable logging and application insights to review important information. After deploying model endpoint is created which we consumed. Finally we create and publish the pipeline to Automate the whole process.

## Architectural Diagram

![Alt text](images/Architecture-Diagram.png?raw=true "Architectural Diagram")

## Key Steps

#1-Dataset Registration

First we upload and register the bankmarketing dataset in the AzureML Studio. the screenshots shows the detials of the bankmarketing dataset 

![Alt text](images/Dataset_1.PNG?raw=true "Dataset Detail")

![Alt text](images/Dataset_2.PNG?raw=true "Dataset Explore")

#2-AutoML Experiment

In this step we created the AutoML Experiment. First we choose the bankmarketing dataset, then we name our experiment "AutoML-Experiment" choose y as target column and created Standard_DS12_v2 compute cluster with maximum 4 number of nodes. In the next step we choose exit criterion 1 and concurrency 5, choose classification and enabled deeplearning. Finally we finised and after about half an hour Experiment is completed.

Bleow screenshots shows the whole steps

![Alt text](images/AutoMLRun_1.PNG?raw=true "AutoML Steps")

![Alt text](images/AutoMLRun_2.PNG?raw=true "AutoML Steps")

![Alt text](images/ComputeCluster_1.PNG?raw=true "Compute Cluster setp 1")

![Alt text](images/ComputeCluster_2.PNG?raw=true "Compute Cluster step 2")

![Alt text](images/AutoMLRun_3.PNG?raw=true "AutoML Steps")

![Alt text](images/AutoMLRun_5.PNG?raw=true "AutoML Steps")

![Alt text](images/ExperimentRun-Completed.PNG?raw=true "AutoML Steps")

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
