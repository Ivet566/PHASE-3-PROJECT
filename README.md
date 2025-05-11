# Phase_3_Project

## SYRIATEL CUSTOMER CHURN ANALYSIS.

## OVERVIEW

The project entails building a classifier to assist the client, SyriaTel Telecommunications, determine whether a customer will soon stop doing business with them.


### OBJECTIVES

1)To Identify factors that have a relation with the customer churn rate
2)Develop a predictive model that uses above identified factors to predicted possibility of customers churning
3)Evaluate the performance of the model against an alternate model and fine tune it for optimal performance

## DATA UNDERSTANDING AND ANALYSIS
### Source of Data

The data set used is obtained from Kaggle and can be obtained by the following link: https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset/data


### Description of Data

The main features analyzed are;
- Customer service calls
- Total day charge
- Total day minutes
- Total eve minutes
- Total eve charge
  
The data set did not have any missing values, it had 3333 rows and 21 columns before any preprocessing was done.

## MODELING
The models used in this case are classification models, as the intention is to determine whether a customer will drop off or not. In this particular project we settled on the logistic regression and used the decision tree model as a comparison model.The data set had several features and thus after determining their relation with the churn rate, among the influential features were customer service calls,total day charge,total day minutes
A number of steps were undertaken during modeling geared towards having a workable data set fit for creating a good perfoming model.

These included:
1)Data encoding – converting to numerical values
2)Data scaling – to be on the same scale
3)Data balancing – To prevent bias in prediction due to data set imbalance


## EVALUATION
The final f1_score obtained from the logistic regression model after all data processing was:

Train data – 0.65
Test data – 0.45
The accuracy of the model in performing predictions was found to be 0.82.
The variation in the f1_score can be explained by the unknown nature of the test data.

![alt text](image.png)


## RECOMMENDATIONS
-Further tuning be done to improve the perfomance of the model especially with regards to the f1-score.

-More focus can be put into modifying or upgrading some customer features that have high correlation with the churn rate, such as customer service calls,total day charge,total day.

-More classification models can be used to further predict the data set with an aim of attaining the most efficient model.



