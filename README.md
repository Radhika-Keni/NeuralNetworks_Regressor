# NeuralNetworks Regressor
Build  a Neural Network Regressor to determine signal strength of an manufacturing equipment


## Objective of this notebook
- The purpose of this notebook is to build a Neural Network Regressor to determine signal strength of an manufacturing equipment
- Details of the **problem statement**  , **data set** ,  **input screenshot** , **summary of the code/solution** and **final result** of the project are listed in the sections to follow.

## Problem Statement 
A communications equipment manufacturing company has a product which is responsible for emitting informative signals. Company wants to build a machine learning model which can help the company to predict the equipment’s signal quality using various parameters.


## Data Description:
The data set contains information on various signal tests performed:
- Parameters: Various measurable signal parameters.
- Signal_Quality: Final signal strength or quality

## Domain:
Electronics and Telecommunication

## Sample Input
Below shows a screen shot of the input data 
![image](https://user-images.githubusercontent.com/68383273/193481175-443c5205-41bd-488b-829d-45f72999676a.png)


## Summary of the Solution/Code:
The code aims at building a Neural Network Regressor
- We begin by doing an Exploratory Data analyses which involves univariate, bivariate and multivariate analysis
- We then perform pre-processing on the data to remove outliers and treat null values
- We contiue pre-processing of the data to prepare it so it can be fed into a Neural Network which involves normalising the input data 
- We then begin the process of building a Neural Network model 
- We bein with a basic Neural Network and capture a baseline "mae" score(chosen metric for regression analysis is MAE)
- Next we  start "tuning" the model in terms of no of hiden layers & try different activation functions and capture scores for each case 
- Finally we compare the test/validation scores for all the various models built above and choose the best contender
- Refer **python worksheet Project_RegressionUsingNeuralNetworks_ElectronAndTelDomain.ipynb** for the solution


## Result
![image](https://user-images.githubusercontent.com/68383273/193481447-1f68b976-565f-4006-a4e0-87327482f313.png)
![image](https://user-images.githubusercontent.com/68383273/193481509-dc258093-a125-4743-bf19-139c48e1da5b.png)





