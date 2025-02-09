# deep_learning-challenge

The following module allows us to use our knowledge of machine learning and neural networks to effectively create a binary classifier. This classifier shall be utilised to assess applicants with funding and the possibility of success on their ventures. 

# Report 
## Overview
Alphabet Soup aims to improve funding decisions through the use of machine learning, in predicting an organization's success. The project specifically implemented a binary classifer using TensorFlow. 
## Results 
### Data Preprocessing
* Target Variable: IS_SUCCESSFUL
* Feature Variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
* Removed Variables: EIN and NAME

### Compiling, Training, and Evaluating the Model
* Three hidden layers, with 80, 30 and 15 neurons respectively.
* Used relu activation.
* Used Sigmoid activation for output layer.
* I was not able to achieve the target model performance of 75% accuracy.
Optimization Attempts
* The first attached image shows the original accuracy of around 73.2%
* The second image shows the first attempt where we added a third layer, accuracy slightly decreased to 73.18%
* The third image shows the second attempt where I changed the output layer activation to relu, accuracy decreased to 72.9%
* The fourth image is the third attempt, where I changed the epoch to 100, accuracy remained around 73.2%.

## Summary 
The changes made did not significantly improve accuracy. A future recommendation would be to use different machine learning models such as Random Forest, which could increase accuracy of our findings.  



