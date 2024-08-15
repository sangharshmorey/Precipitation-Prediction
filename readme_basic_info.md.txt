Dataset: Downlaod the dataset to begin with your Final Project, For downloading individual files form Github use "GitZip for github" chrome extension
Precipitation(PRCP) column in the data frame will be our target feature in this model. Replace all values greater than 0 as 1 (representing precipitation will occur), and values that are equal to 0 representing precipitation will not occur
Dropping null values : Drop any column that has an excessive number of null values. For the remaining columns with a lower number of null values, replace those null values with the mode of that column.
EDA : Perform EDA to visualize data and identify outliers
Data Preprocessing : Remove outliers and find corelation matrix
Use SMOTE to handel class imbalance : Most of the ML algorithms used for classification were designed with the assumption of an equal no. of examples in each case. Therefore we need to balance it. The imbalance has to be removed or reduced.
Check for null values once again and proceed
Feature selection : Feature selection will be made using the chi-square test, refer SelectKBest and chi2
Normalise the dataset
Training model using different techniques
Split data into test and train datasets.
Use logistic regression classifier, decision tree classifier, neural networks training dataset.
Calculate accuracy, precision, recall, F-1 score, and ROC_AUC on the test dataset and visualize it.
Plot confusion matrix using sklearn.
Kindly refer to the documentation provided on Google to perform the above steps
Model Comparison : Compare models based on accuracy and ROC_AUC score and visualize it using seaborn