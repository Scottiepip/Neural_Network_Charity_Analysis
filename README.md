# Neural_Network_Charity_Analysis

## Overview:
From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

With our knowledge of machine learning and neural networks, we’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.


## Result:

### Data Processing
- Variable IS_SUCCESSFUL was considered the target for the model.
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT was considered as the features for the model.
- The columns EIN and NAME were neither targets nor features, so it was removed from the input data.

### Compiling, Training, and Evaluating the Model
- The neural network has 2 hidden layers, the first layer has 80 neurons and the second has 30 neurons. The activation function of the first and second hidden layers is "relu" and the activation function of the output layer is "sigmoid".

- The model only achieve an accuracy of 72.97%, couldn't achieve the target model performance of 75%.

- Change neurons in hidden layers, add additional hidden layer, change activation function in hidden layers.

### Summary:
I tried to optimize the neural network model by increasing neurons in hidden layers, adding additional hidden layers and changing hidden layers' actiovation function.
the optimized model is not outperforming the original model. But changing the activation function in the hidden layers from "relu" to "sigmoid" did increase the accuracy slightly to 73.12%.

We can try to use a supervised machine learning model such as random forest classifier to solve this classification problem. The random forest model is able to achieve comparable predictive accuracy on large tabular data with less code and faster performance.
