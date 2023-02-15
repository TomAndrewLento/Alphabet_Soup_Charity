# Overview
Use a CSV containing more than 34,000 organizations to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

# Results
## Data Preprocessing
* 'IS_SUCCESSFUL' is the target variable.  The model will use this to predict whether the applicants will be funded by Alphabet Soup.
* APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT were the features
* EIN and NAME were identifiers removed from the input data

## Compiling, Training, and Evaluating the Model
* My model had 2 layers with 30 neurons in the first and 22 in the second
* The best model performance I could achieve was 68%
* I added more neurons 

# Summary
* A random forest can be used alongside this deep learning model in order to measure which features played the strongest role in determining the target variable
