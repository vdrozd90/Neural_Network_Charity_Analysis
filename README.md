# Neural_Network_Charity_Analysis

## Overview of the analysis: 

The purpose of this analysis is to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 

### Data Preprocessing
- "IS_SUCCESSFUL" is the target variable for the model
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL. Are considered to be the features for the model
- "EIN" and "NAME" are neither targets nor features, and have been removed from the input data

### Compiling, Training, and Evaluating the Model
- Attempt 1 of the model contained 2 hidden layers. Hidden layer 1 had 18 neurons, and 9 neurons in the second layer. Hidden layers had activation function of relu, output activation was sigmoid. 
- The target model performance was not achieved on attempt 1 of creating the neural network model. The models accuracy was approximately 70%
- Attempts were taken to try increasing the accuracy of the model. Optimization 1: number of neurons and epochs were changed resulting in accuracy falling to 68%. Optimization Attempt 2: add a third hidden layer, increase the number of neurons, reduce the number of epochs, resulting in accuracy falling to 53%. Optimization Attempt 3: back to 2 hidden layers, change output activation to "tanh", and change number of epochs, resulted in accuracy around 53%.

## Summary: 
Overall the first model had the highest accuracy of 70%. Through running the optimizations I was able to see how adding or reducing the number of hidden layers, neurons and epochs changed the accuracy of the model. 
