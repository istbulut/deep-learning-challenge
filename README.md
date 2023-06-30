# deep-learning-challenge

In this assignment given by Birmingham University Data Boot Camp, using machine learning and neural networks, a binary classifier is created to predict if the applicants of the nonprofit foundation Alphabet Soup will be successful if they were funded by Alphabet Soup. For this purpose, data of 34299 rows * 12 columns has been analyzed. 

The futures are:
•	EIN and NAME—Identification columns
•	APPLICATION_TYPE—Alphabet Soup application type
•	AFFILIATION—Affiliated sector of industry
•	CLASSIFICATION—Government organization classification
•	USE_CASE—Use case for funding
•	ORGANIZATION—Organization type
•	STATUS—Active status
•	INCOME_AMT—Income classification
•	SPECIAL_CONSIDERATIONS—Special considerations for application
•	ASK_AMT—Funding amount requested.

Target variable is:
•	IS_SUCCESSFUL—Was the money used effectively.

 - In the first part of the study, data has been preprocessed by dropping identification columns, checking unique values, creating bins for CLASSIFICATION and APPLICATION_TYPE columns, converting categorical data to numeric, scaling the data, identifying future and target arrays, splitting the data as train – test.  Then, binary classification model, compiled, trained, and evaluated to calculate the model’s loss and accuracy which were found as Loss: 0.5617768168449402, Accuracy: 0.7254810333251953.

 - In the second part, optimization methods such as droping some columns, creating bins, increasing or decreasing the number of values for each bin, adding more neurons to a hidden layer, adding more hidden layers, using different activation functions for the hidden layers, adding or reduce the number of epochs to the training regimen have been applied to the model to achieve a target predictive accuracy higher than 75%. 




