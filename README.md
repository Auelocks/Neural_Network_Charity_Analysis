# Neural_Network_Charity_Analysis

## Overview
This project will us machine learning and neural networks to create a binary classifier capable of predicting whether charity will be successful if funded.  The script is written in Python utilizing Jupyter Notebook and the sklearn and tensorflow libraries.

## Results
### Data Preprocessing

   * The target for this model is whether the charity funded was successful which, in this dataset is “IS_SUCCESSFUL” and was assigned to the “y” variable.
 
   * The variables selected as features include:
     * APPLICATION_TYPE—Alphabet Soup application type
     * AFFILIATION—Affiliated sector of industry
     * CLASSIFICATION—Government organization classification
     * USE_CASE—Use case for funding
     * ORGANIZATION—Organization type
     * INCOME_AMT—Income classification
     * SPECIAL_CONSIDERATIONS—Special consideration for application
     *  ASK_AMT—Funding amount requested

   * The variables deemed to have the least significant impact on the target value and were therefore removed from the dataset include identification columns EIN and NAME, and the charities with inactive status.

### Compiling, Training, and Evaluating the Model

   * Two hidden layers with the RELU function and an output layer with the sigmoid activation function were selected for this model.
   * The target model performance of 75% was not reached.
   * It is recommended to try reducing the feature variables further and try utilizing other machine learning methods which may offer more control and better performance on this dataset.


## Summary
Overall, the model was able to achieve 73% which is close to the target value, however, several tries of changing node layers and input dimensions made no significant impact.  It is recommended to try other machine learning methods such as Random Forest which often offers high predictive accuracy.
