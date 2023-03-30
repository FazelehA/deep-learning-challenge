# deep-learning-challenge

## Overview

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using knowledge of machine learning and neural networks, the features in the provided dataset were used to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

A CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years was recieved from Soup’s business team. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

## Results

* Data Preprocessing

    * The target variable for the model is "IS_SUCCESSFUL"
    * The features of the model are:
          *APPLICATION_TYPE
          *AFFILIATION
          *CLASSIFICATION
          *USE_CASE
          *ORGANIZATION
          *STATUS 
          *INCOME_AMT
          *SPECIAL_CONSIDERATIONS
          *ASK_AMT
    * EIN and NAME were removed from the input data because they are neither targets nor features.
 
 * Compiling, Training, and Evaluating the Mode
      
      * Attempt 1: 2 hidden layers with 80 and 30 neurons
      * Attemp 2: 3 hidden layers with 80, 30 and 30 neurons
      * Attempt 3: 2 hidden layers with 80 and 30 neurons and 50 epochs

## Summary 

Attempt 1 achieved an accuracy of 72.8%. Optimising the model by adding a hidden layer and reducing the number of epochs only imporved the accuracy slightly to 72.9%. Further optimisation is needed to achived the desired accuracy of 75%.
