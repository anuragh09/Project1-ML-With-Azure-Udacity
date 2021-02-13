# Optimizing an ML Pipeline in Azure

## Overview
This project is part of the Udacity Azure ML Nanodegree.
In this project, we build and optimize an Azure ML pipeline using the Python SDK and a provided Scikit-learn model.
This model is then compared to an Azure AutoML run.

## Summary
In this project we used the data from the banking institution database which contains the data about its customers including age, contact, loans and other relations with the bank.
The dataset contains 32950 rows and 20 column features. The goal of the model is to predict if the customer will subcribe for the term deposits. 

The solution was found using hyperdrive as well as another run was performed by AutoML.  
Using the Hyperdrive and logistic regression algorithm, 91.28% accuracy was achieved whereas running AutoML, accuracy of 91.71% was achieved. Among all the ML algorithms ran my AutoML VotingEnsemble model was best performing.

## Scikit-learn Pipeline
**Explain the pipeline architecture, including data, hyperparameter tuning, and classification algorithm.**

**What are the benefits of the parameter sampler you chose?**

**What are the benefits of the early stopping policy you chose?**

## AutoML
**In 1-2 sentences, describe the model and hyperparameters generated by AutoML.**

## Pipeline comparison
**Compare the two models and their performance. What are the differences in accuracy? In architecture? If there was a difference, why do you think there was one?**

## Future work
**What are some areas of improvement for future experiments? Why might these improvements help the model?**

## Proof of cluster clean up
**If you did not delete your compute cluster in the code, please complete this section. Otherwise, delete this section.**
**Image of cluster marked for deletion**
