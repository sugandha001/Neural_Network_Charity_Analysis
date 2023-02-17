# Neural_Network_Charity_Analysis

## Overview and purpose of the loan prediction risk analysis:

For this analysis we created a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Based on it we can help determine which organizations should be considered for funding by Alphabet Soup.  From Alphabet Soup’s business team, we used CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.


## Results:

### Variables in the data

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

#### 1. What variable(s) are considered the target(s) for your model?

APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS

##### 2. What variable(s) are considered to be the features for your model?

IS_SUCCESSFUL

#### 3. What variable(s) are neither targets nor features, and should be removed from the input data?

EIN
NAME

### Compiling, Training, and Evaluating the Model

#### 4. How many neurons, layers, and activation functions did you select for your neural network model, and why?

#### ATTEMPT 1 - 

![Screenshot (262)](https://user-images.githubusercontent.com/112904905/219539254-e4ec1740-bb99-4e7b-bac1-642703016dee.png)

#### ATTEMPT 2 -

![Screenshot (263)](https://user-images.githubusercontent.com/112904905/219539634-90876a85-bd8d-411c-9073-5184943ab3be.png)

#### ATTEMPT 3 -

![Screenshot (264)](https://user-images.githubusercontent.com/112904905/219539765-bd8ac435-cb2e-4391-8183-96be073fcd97.png)

#### 5. Were you able to achieve the target model performance?
No. First attempt I got 73 % accuracy (approx). Second attempt I got 46% Accuracy (approx) and Third attempt I got 73 % accuracy (Approx)

#### 6. What steps did you take to try and increase model performance?

- Dropped noisy data
- Added additional hidden layer

#### Summary:
The model did not perform with a high accuracy. Adding more layers did not have a major effect. 
Random Forest Classifier may be a model that may provide better accuracy as it is good for large data sets and we can perform binary classification. 
