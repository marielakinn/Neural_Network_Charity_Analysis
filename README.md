#Neural Network Charity Analysis

## Project Overview and Purpose

The purpose of this project is to use Machine Learning and Neural Networks to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
The following assignments were completed:

- Preprocessing Data for a Neural Network Model
- Compile, Train, and Evaluate the Model
- Optimize the Model

## Results

### Data Preprocessing
- What variable(s) are considered the target(s) for your model?

  The “IS_SUCCESSFULL” column was considered the target to train the ML model.

- What variable(s) are considered to be the features for your model?

  All columns, except the target variables were considered to be features for this model. 
  
- What variable(s) are neither targets nor features, and should be removed from the input data?
  
  The variables that should be removed and are neither targets nor features are variables that are meaningless for the model.
  
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?

  - 200 neurons were used for the first layer and 90 neurons were used for the second layer bacuase the first layer should have at least double the amount of input features. 
  - Two layers were used because three layers did not contribute much to the improvement of the ML model. The additional layer was redundant.
  - The relu acttivation function was used because it had the best accuracy for this model.
- Were you able to achieve the target model performance?

  Yes. The model accuracy improved to over 76% after optimization. 
  
- What steps did you take to try and increase model performance?

  To increase performance I binned the ASK_AMT values, used two layers with 200 neurons for the first layer and 90 for the second layer, and increased epochs to 500. 

## Summary

In summary, the model has a 61% probability to fail, and a 76% probability to be accurate. Although the model reached the required criteria it might not be the best model for this dataset due to the fact that the loss score is still high at 61%. For this prokect I would reccommend adding more input values or collecting more data if possible to improve the model's performace.
