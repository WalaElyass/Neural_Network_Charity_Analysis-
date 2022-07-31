# Neural_Network_Charity_Analysis-

##  Analysis Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.
We use the following methods for the analysis:

preprocessing the data for the neural network model,
compile, train and evaluate the model,
optimize the model.


##  Results
# Data Preprocessing

The data provided shows a column for 'IS_SUCCESSFUL,' and will be the targeted data point for these predictions.
There are many data points (features) that will be used as input for the models. Included are:

* AFFILIATION
* APPLICATION_TYPE
* ASK_AMT
* CLASSIFICATION
* INCOME_AMT
* ORGANIZATION
* SPECIAL_CONSIDERATIONS
* STATUS
* USE_CASE

The columns for "NAME" and "EIN" have no direct effect on the success/falure rate, and have been excluded from processing.


* Compiling, Training, and Evaluating the Model

Initial preparation for the Sequential Neural Network specified 43 input features, into three processing layers that began with 80 neurons and decreased to 30 and 15, and a single output layer.
The target performance of 75% accuracy was not met (72.75%).
Further testing was done with three dynamic tuned models that statically and dynamically selected inputs, layers, neurons, and activations. These attempts yeilded accuracy results of:
First Model: 73.49%
Second Model: 73.17%
Third Model: 73.51%
Although accuracy was only improved marginally, the total loss of the dynamic deep learning models did offer an excellent decrease in the Loss factor.


## Summary
The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.
Since we are in a binary classification situation, we could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.
