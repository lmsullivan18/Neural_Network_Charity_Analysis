# Neural Network Charity Analysis

## Overview
The purpose of this analysis was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
### Data Preprocessing
- The variable considered the target for this model is "IS_SUCCESSFUL" because we're working to create a classifier that determines if applicants will be successful.
- The variables considered to the be the features for this model are application type, affiliation, classification, use case, organization, status, income amount and ask amount.
- The variables that are neither targets nor features, and should be removed from the input data, are "SPECIAL_CONSIDERATIONS".

### Compiling, Training and Evaluating the Model
- For my neural network model I selectioned 21 neurons, 3 layers and 2 activation functions.
- I was not able to achieve the target model performance.
- To try to increase model performance, I increased the number of neurons, added a layer, and removed some variables that are neither targets nor features.

## Summary
I was not able to get the model to improve beyond 72% accuracy. A model I would recommend trying instead is supervised machine learning. This analysis is very similar to the one we did about loans, as we're again trying to determine good candidates to recieved money from an isntitution. We know the result we're looking for (a good candiate vs. a bad candidate) so I believe this would be good analysis to test.
