# Neural_Network_Charity_Analysis

### Overview

The purpose of this analysis is to apply a “deep learning model” to predict which organizations funded by AlphabetSoup ™ will be successful and therefore should receive donations. Using historical data that contains approximately 34,000 records of organizations funded by AlphabetSoup, three steps were performed as follows:

•       Preprocessing the data for the neural network

•        Compilation, training and evaluation of the model

•        Final optimization of the model

### Results:

### Data Preprocessing:
•       The variable being targeted in this module is the ‘IS_SUCCESSFUL’ column.

•       The features being used are every column except the ones that we will drop.

•       The ‘EIN' & 'NAME' variables were removed as neither were targets nor impacted the outcome of the analysis.

### Compilation, training and evaluation of the model:

The model is made up of the following: An input feature and two hidden layers which were chosen for categorical output purposes.

•  Hidden layer 1 has 80 neurons, activation function “relu”
•  Hidden layer 2 has 30 neurons, activation function “sigmoid”
•  Output layer, activation function “sigmoid”

Our model target was 75%, unfortunately, we were not able to achieve it.

•   Some of the attempts applied to help increase model performance were as follows:
•  Adding the number of hidden layers and the number of neurons 

### Summary:

The purpose of this project was to attempt to determine which organizations funded by AlphabetSoup would succeed and should receive donations by applying a deep learning model. The accuracy target performance for this prediction was 75% which unfortunately was not achieved.  Instead, the model accuracy was slightly lower at 72%. Perhaps, dropping more features and focusing more on variables that impact our outcomes would have helped. For future analysis, maybe using more solid/concrete data could help increase the accuracy of the model.

