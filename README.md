# breast-cancer-detection

This project is about breast cancer detection by logistic regression.



Logistic Regression

Logistic regression is a supervised machine learning algorithm used for classification tasks where the main aim is to predict  
the probability based on prior  observations  of a dataset to give a class or not. Logistic regression is a statistical algorithm 
that predicts the value of a dependent variable by analyzing the relationship between one or more existing independent variables.  

Logistic regression is used for binary classification where we use a sigmoid function that takes input as independent variables 
and produces a probability value between 0 and 1. Logistic regression has many applications in science, also in healthcare can 
drive life-changing action. 




Description

In this project, breast cancer is detected by applying a logistic regression model on a real-world data set and predicting whether
a tumor is benign (not breast cancer) or malignant (breast cancer) based on its characteristics. The data is collected from the UC Irvine 
machine learning repository and this is the breast cancer wisconsin original data. 


This logistic regression model is to identify correlations between the following 9 independent variables and the class of the 
tumor (benign or malignant).

Clump thickness
Uniformity of cell size
Uniformity of cell shape
Marginal adhesion
Single epithelial cell
Bare Nuclei
Bland chromatin
Normal nucleoli
Mitoses



Logistic regression can identify important predictors of breast cancer using odds ratios and generate confidence intervals that 
provide additional information for decision-making. 


1. Data Preprocessing
Importing the dataset
Splitting the dataset into a training set and test set

2. Training and Inference
Training the logistic regression model on the training set
Predicting the test set results

3. Evaluating the Model
Making the confusion matrix
Computing the accuracy with k-Fold cross-validation

