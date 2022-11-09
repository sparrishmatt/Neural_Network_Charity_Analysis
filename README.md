# Neural Network Charity Analysis

## Purpose of analysis
The goal of this analysis was to predict which startups were most likely to succeed if given funding from Alphabet Soup. This will be done through the use of a neural network that will be trained through the use of the tensorflow sklearn extensions. 

## Results
### Target and feature analysis

The target variable for this analysis is 'is_successful' which is used to show if the startup is successful. It is the target because the goal is to predict if future startups will also be successful or not. 

The feature variables that will be used to train the neural network are application type, affiliation, classification, use case, organization, status, income amount, ask amount, and whether or not there are special considerations. There are also variables that are neither target nor feature variables: EIN and Name.

### Neural Network

<img src="https://github.com/sparrishmatt/Neural_Network_Charity_Analysis/blob/main/Resources/model.png" width="750">

As can be seen above, the neural network has two hidden layers both with 55 neurons as well as two relu activation functions. The cause for the activation functions was using relu functions for similar datasets prior to this point, and the neuron counts came after trying different counts just to see the results and settling there. 

The goal accuracy for this neural network was 75% which was not reached, however small performance gains happened as changes to the model were made. By adding another hidden layer, more neurons, and changing some of the activation functions a final accuracy of 72.6% was achieved. 

## Summary 

Updated summary to come later. 



