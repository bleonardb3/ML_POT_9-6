# Train and deploy a heart disease prediction model using XGBoost and IBM Watson Machine Learning APIs

## Introduction:

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/DSX.png" height="150"/>](http://datascience.ibm.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/jupyter.png" height="150"/>](http://jupyter.org/index.html)

In this lab, you will use a Jupyter Notebook to train a model using the XGBoost library to classify whether a person has heart disease or not In addition to training, the notebook also explains how to persist a trained model to the IBM Watson Machine Learning repository, deploy the model as a REST service and to predict using the deployed model using the REST APIs.

In order to train and test the heart disease prediction model, you will be using an open source data set published in the University of California, Irvine (UCI) Machine Learning Repository.

The notebook uses Python 3.5 runtime, XGBoost 0.6 and Scikit-Learn 0.17.

## Objectives:

Upon completing the lab, you will know how to:

1. Load a CSV file into Pandas DataFrame.
1. Data exploration using Pixiedust
1. Prepare data for training and evaluation.
1. Create, train, and evaluate a XGBoost model.  
1. Visualize a decision trees used by the model.
1. Visualize the importance of features that were used to train the model.
1. Use cross validation to select optimal model hyperparameters based on a parameter grid
1. Persist best model in Watson Machine Learning repository using Python client library.
1. Deploy the model for online scoring using the Watson Machine Learning's REST APIs
1. Score sample data using the Watson Machine Learning's REST APIs.

## Instructions:

### Step 1.  Log into your [Watson Studio](http://datascience.ibm.com/) account, then select `View All Projects`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/View%20All%20Projects.png"/>

### Step 2.  Select the project you created at the beginning of this proof of technology.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Watson%20Studio%20Labs.png"/>

### Step 3.  We are now going to create a new notebook in our project. This notebook will be created from a url that points to the Heart Disease notebook in the github repository. Click the `Add to project` link and then the `Notebook` link as shown below. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Add%20Notebook.png"/>

### Step 4.  Create the notebook.

> <img src="https://github.com/bleonardb3/ML_POT_9-6/blob/master/Lab-1/images/Create%20Heart%20Disease%20Notebook.png"/>

1. Click the `From URL` tab under `New Notebook`.
1. Give the notebook a name in the `Name` field, for example `Heart Disease` and optionally you can give it a description.
1. In the Notebook URL field, use `https://github.com/bleonardb3/ML_POT_9-6/blob/master/Lab-1/Heart%20Disease.ipynb`.
1. Select the Spark environment that you created, then click the `Create Notebook` button on the bottom right of the screen.

### Step 5.  Follow the instructions in the notebook.


