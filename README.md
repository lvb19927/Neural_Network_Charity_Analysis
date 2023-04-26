# Neural Network Charity Analysis
## Overview:
This project is to use deep_learning neural networks with Tensorflow in Jupyter Botebook wiht Python to show the success of charitable donations. We trained a model and continued with layering methods to optimize the model results.
## Results:
### Data Preprocessing
- The 'IS_SUCCESSFUL' column contains binary data to show the effectiveness of the charity donations. **TARGET**
- Variables considered **FEATURES**: `APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT`
- Columns 'EIN' and 'NAME' are removbed since they are only for identification.
### Compiling, Training, and Evaluating the Model
- The neural network consists of two hidden layers: 80 and 30 neurons.
- 43 features and 25,724 samples.
- Activation functions used: 'ReLU' & 'Sigmoid'
- Target model performance was not achieved, but only by 3%
- To increase performance, attemped to buvket different features, increased the number of neurons in the hidden layers and used a model with three hidden layers as well as function 'tanh'.

## Summary
The deep learning neural network model did not reach performance accuracy desired. A recommendation would be to use something along the lines of a Random Forest Classifier to combine the decision trees to create a classified output and compare it against the deep learning model.
