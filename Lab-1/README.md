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

The labs in this Proof of Technology will require the following services to be created and associated with your project. 
1. Object Storage
1. Watson Machine Learning
1. Apache Spark  

The Object Storage service instance should already exist, having been created when the Watson Studio Labs (or whatever you named it) project was created. Both the Watson Machine Learning service, and the Apache Spark service need to be created and then associated with the project.  

### Step 3.  Click on the project `Settings` tab.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Settings.png"/>

### Step 4. Scroll down to `Associated Services`, then select `Add service` and select `Machine Learning`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Add%20Machine%20Learning%20Service.png"/>

### Step 5. Select `New`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20New%20Service.png"/>

### Step 6. Select the `Lite` plan. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Lite%20ML.png"/>

### Step 7. Scroll down and click `Create` and then click `Confirm`. Note, you can change the name of the machine learning service or accept the default. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Scroll%20down%20hit%20Create%20and%20then%20Confirm.png"/>

### Step 8. The Machine Learning service that you created should now appear in `Associated Services`. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/See%20ML%20in%20Associated%20Services..png"/>

### Step 9. Follow the same process as in steps 4-8, except this time add a Spark service. 


### Step 10.  We are now going to create a new notebook in our project. This notebook will be created from a url that points to the Heart Disease notebook in the github repository. Click the `Add to project` link and then the `Notebook` link as shown below. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Add%20Notebook.png"/>

### Step 11.  Create the notebook.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Create%20Notebook%20Lab-1.png"/>

1. Click the `From URL` tab under `New Notebook`.
1. Give the notebook a name in the `Name` field, for example `Heart Disease` and optionally you can give it a description.
1. In the Notebook URL field, use `https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/Heart%20Disease.ipynb`.
1. Select the Spark environment that you created, then click the `Create Notebook` button on the bottom right of the screen.

### Step 12.  Follow the instructions in the notebook.


