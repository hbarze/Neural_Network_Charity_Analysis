# Neural_Network_Charity_Analysis

Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively
 
## Analysis Overview

This analysis focuses on the development of a neural network to help Beks choose make a platform that helps the foundation predict where to make the most promising investments. 

## Results:

Data Preprocessing

* What variable(s) are considered the target(s) for your model?
- The variable that's the target of the model is the "IS_SUCCESSFUL" variable. This determines if the charity is worth funding. 

* What variable(s) are considered to be the features for your model?
- The variables that are the features of the model are "BINARY_CROSSENTROPHY", "ADAM", and "ACCURACY"

* What variable(s) are neither targets nor features, and should be removed from the input data?
- The variables that need to be dropped are the "EIN" and "Name" variables. 

Compiling, Training, and Evaluating the Model

<img width="546" alt="Screen Shot 2022-05-17 at 10 06 27 PM" src="https://user-images.githubusercontent.com/96043107/168948978-e1b5545f-3ea7-4e3b-b79e-53f1e2ca0ce8.png">

<img width="530" alt="Screen Shot 2022-05-17 at 10 06 57 PM" src="https://user-images.githubusercontent.com/96043107/168949038-cd395179-8351-401f-808f-b38b7f2069f4.png">


* How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Initially, the number of neurons, layers, and activation functions were 80, 30, and 1. Additional layers were added in the next attempts.  

* Were you able to achieve the target model performance?
- No, I was not able to achieve the target model performance at above 75% accuracy. 

* What steps did you take to try and increase model performance?
- I tried to increase the number of neurons/layers in the new attempt. 

## Summary:

Deep learning and neural networks can be a great tool in a decision making process involving several different inupts and outcomes, and with matricies in general. However, I did not reach the target model performance like the Module challenge asked for. In further attempts, I would try and decrease the number of neurons and layers, and adjust the number of activation functions. 
