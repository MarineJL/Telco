# :telephone_receiver: Telco

![badge](https://img.shields.io/badge/language-R-blue.svg)

This work is based on the dataset - [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn) from Kaggle.
It is a data snapshot of the customers of a telecom company which provides phone and internet service. :phone:

Our business problem is to fight against customer churn. Our company wants to predict which customers are more likely to churn so that we can take the necessary actions to retain them.

## :books: Table of content

- [Data Cleaning and Exploratory Analysis](#detective-Data_Cleaning_and_Exploratory_Analysis )
- [Machine Learning](#computer-MachineLearning)
- [Authors](#pen-Authors)
- [Support](#hammer_and_wrench-support)
- [Contributing](#memo-contributing)

## :detective: Data Cleaning and Exploratory Analysis 

Let's clean the data set and do a first exporatory analysis to check what's the data look like. Results can be found in the Rmd file

## :computer:  Machine Learning

This is a classification problem, we want to predict which customers are more likely to churn. 
In the Rmd file, you can find different algorithms applied to the dataset
- Logistic Regression
- Stepwise selection
- Penalized Regression (Ridge, Lasso)
- KNN Classification
- Trees and Random Forests

In order to select the best model, we compare them using the following criteria: 
-Accuracy
-Specificity
-ROC and AUC methods

## :pen: Authors

-DEVOS Pierre-Yvan
-JACQUEMIN-LORRIAUX Marine
-LEGENDRE Benoit
-SHAH Ashay

## :hammer_and_wrench: Support

Please [open an issue](https://github.com/MarineJL/Telco/issues/new) for support.

## :memo: Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/MarineJL/Telco/compare/).
