# Botson-Housing-Price-prediction-
In this project, we will develop and evaluate the performance and the predictive power of a model trained and tested on data collected from houses in Boston’s suburbs. The list of tasks below : 
1) Exploratory Analysis using ggplot2 
2) Splitting the dataset into Train and Test (7:3 Combinations) 
3) Predict the accuracy of Random forest, Linear Regression and XGBoost classification model. 
4) Compare the multiple models using RMSE

# Source of dataset:
The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository).

Features of dataset:

0.CRIM: per capita crime rate by town

1. ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
2. INDUS: proportion of non-retail business acres per town
3. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
4. NOX: nitric oxides concentration (parts per 10 million)
1https://archive.ics.uci.edu/ml/datasets/Housing
123
20.2. Load the Dataset 124
5. RM: average number of rooms per dwelling
5. AGE: proportion of owner-occupied units built prior to 1940
7. DIS: weighted distances to ﬁve Boston employment centers
8. RAD: index of accessibility to radial highways
9. TAX: full-value property-tax rate per $10,000
10. PTRATIO: pupil-teacher ratio by town 12. B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town 13. LSTAT: % lower status of the population
11. MEDV: Median value of owner-occupied homes in $1000s
We can see that the input attributes have a mixture of units.

# Exploratory Analysis using ggplot2 

Correlation matrix :
![image](https://user-images.githubusercontent.com/65977290/125964062-834c44da-9200-4d34-8b33-07cca467cb8f.png)

GGplot between different features:

![image](https://user-images.githubusercontent.com/65977290/125964125-274243fc-2a62-4759-845c-c8e4684aebca.png)



![image](https://user-images.githubusercontent.com/65977290/125964155-a2502c72-8eaf-436a-b9d7-79f66b1b4fe7.png)

# Predict the accuracy of Random forest, Linear Regression and XGBoost classification model. 

   Model           R-squared Score
   
   Random Forest   85.952494
   
   
   XGBoost         84.602124
   
   Linear Regression 70.876693
   
# Compare the multiple models using RMSE
  
  Model              Root Mean Sqaure Error(RMSE)
  
  Random Forest      1.1437549740560535
  
  Linear Regression  4.5624434924610995
  
  XGBoost            0.01156838856617691

   
   

