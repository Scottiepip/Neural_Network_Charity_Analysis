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

- The model only achieve an accuracy of 73%, couldn't achieve the target model performance of 75%.

- Change neurons in hidden layers, add additional hidden layer, change activation function in hidden layers.

### Summary:

