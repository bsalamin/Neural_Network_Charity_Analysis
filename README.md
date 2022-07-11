# Neural_Network_Charity_Analysis

## Overview
The objectives of this analysis are to:
* Compare the differences between the traditional machine learning classification and regression models and the neural network models.
* Describe the perceptron model and its components.
* Implement neural network models using TensorFlow.
* Explain how different neural network structures change algorithm performance.
* Preprocess and construct datasets for neural network models.
* Compare the differences between neural network models and deep neural networks.
* Implement deep neural network models using TensorFlow.
* Save trained TensorFlow models for later use.

The final deliverable is a binary classifier that is capable of predicting whether applicants will be successful if funded by the charity.


## Results
* The column 'IS_SUCCESSFUL' contains binary data for charity donation sucess and is the target for this model.
* The columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', 'ASK_AMT' are the features for this model.
* The columns 'EIN' and 'NAME' contain only identifying information and are neither targets nor features, so they were removed from the input data.
* This deep-learning neural network model utilizes: 
  * Two hidden layers with 80 and 30 neurons, respectively.
  * Input data with 40 features and 25724 samples.
  * Activation function 'ReLU' for hidden layers, and then the  activation function 'Sigmoid' is used in the output layerm, because of the binary classification.
* The target model performance of 75% accuracy was not acheived.
* To try to improve the performance/accuracy, the model was optimized by:
  * Adding additional hidden layer to the neural network.
  * Increasing the number of neurons for some of the hidden layers.
  * Changing the number of epochs in the training regimen.
  * Altering the activation functions of the hidden layers from 'ReLU' to 'tanh'
  * Combining these changes into one smorgus board of a training model.

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
