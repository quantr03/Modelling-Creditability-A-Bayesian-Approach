# Modelling-Creditability-A-Bayesian-Approach

# Bayesian Analysis of Esophageal Cancer Risk Factors: Evaluating the Role of Age, Tobacco, and Alcohol Consumption
Course project for CS-E5710 - Bayesian Data Analysis D

Modeling the likelihood of developing Esophageal Cancer from a Bayesian perspective

Author: Quan Tran


## Introduction

This project is part of the Aalto University Bayesian Data Analysis 2023 Course. 

In the intricate world of financial behavior, creditability stands as a cornerstone, reflecting a myriad of socio-economic factors. Our investigation is underpinned by a sophisticated logistic regression model, meticulously crafted within a Bayesian framework. This methodological choice not only allows us to capture the nuanced interplay between individual predictors and creditability but also to discern the subtle yet significant influences exerted by occupational categories. As we navigate through this labyrinth of data, our analysis is not just about crunching numbers; it’s a quest to uncover the hidden stories behind creditworthiness. Each statistical insight offers a deeper understanding of the financial fabric that binds individuals and occupations, providing valuable perspectives for both risk assessment and strategic financial planning.

## Data description
The German Credit Data was obtained from the [Kaggle](https://www.kaggle.com/datasets/mpwolke/cusersmarildownloadsgermancsv/data) website. The data contains data 20 explanatory variables and 1 response variable, which is the classification of whether an applicant is considered a Good or a Bad credit risk, for 1000 loan applicants.

## Results

The Hierarchical model is performing strictly better in some aspects. The two metrics we would focus on are Precision and Specificity. Since the cost false positivity is high (the loss of lending who would default eventually outweighs the profit gained), the Precision and Specificity metrics are appropriate since they put emphasis on the classifier’s exactness. Even if the two models have quite good Precision scores (0.8 and 0.81 for the Pooled model and the Hierarchical model respectively), the Specificity scores are quite humble (0.51 and 0.53 for the Pooled model and the Hierarchical model respectively). Therefore, these models should be refined before being deployed in practical use.
