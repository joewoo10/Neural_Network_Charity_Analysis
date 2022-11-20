# Neural_Network_Charity_Analysis

## Project Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.

## Results

## Data Preprocessing 

### *What variable(s) that are considered the target(s) for your model?*

The variable targeted in this module is the “IS_SUCCESSFUL” column.

### *What variable(s) that are considered to be the features for your model?*

The features used are all columns except the ones that will be dropped.

### *What variable(s) are neither targets nor features were removed?*

Features dropped are the 'EIN' & 'NAME' because they both are features that have little to do with the outcome.


## Compiling, Training, and Evaluating the Model

### *How many neurons, layers, and activation functions did you select for your neural network model?*

This model is made with an input features and two hidden layers. The first hidden layer has 80 neurons, while the second has 30. There is also an output layer. Each layer has an activation function. The first and second hidden layers have the activation function "relu" and the output layer’s activation function is "sigmoid".

![image](https://user-images.githubusercontent.com/109227896/202915767-6b55a56e-312f-4a54-a080-7d718189506d.png)


### *Was the model able to achieve the target model performance?*

The target for the model was higher than 75% accuracy, however I was not able to achieve that target.

### *What steps were taken to try and increase model performance?*

I tried several things to increase the accuracy of the model. I added hidden layers, changed the activation functions, altered the number of epochs and changed the number of neurons in each layer. Many adjustments resulted in lowering the accuracy of the model. The image below shows the highest accuracy I was able to achieve.

![image](https://user-images.githubusercontent.com/109227896/202915819-ccb4f608-45f4-4205-8a9c-3f68c2f34f6d.png)


## Summary

The final model accuracy ended up being 70.36%. We were provided a data set and tried to predict whether the project would be successful on all the features that we used after dropping two features that were believed to be irrelevant. Although I did not reach the accuracy of >75% that I wanted it is possible the reason for this is we may have needed to drop more features which could have affected how good the neural network is. The best way to increase the accuracy of the model is to have more data. If we have solid data added to this model, the accuracy of this model will be much more concrete.
