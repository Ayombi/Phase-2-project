# Phase-3- Project - SYRIATEL CUSTOMER CHURN
![image](https://github.com/Ayombi/Phase-2-project/assets/151352835/b36c297d-5406-4bdf-a277-406c76ef486c)

__Overview__
Syriatel Ltd is a Telecom company that would like a model to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company. A lot of resources go into understanding whether a customer will leave the company. Having a clear prediction model will assist the customers in costs to invest in and the marketing strategies to retain the customer.
__BACKGROUND__ 
Syriatel Ltd is a Telecom company that would like a model to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company. A lot of resources go into understanding whether a customer will leave the company. Having a clear prediction model will assist the customers in costs to invest in and the marketing strategies to retain the customer.
__BUSINESS AND DATA UNDERSTANDING__
This is a binary classification problem.The problem at hand is to Build a classifier that will assist the tele company predict the rate of the customers leaving to competitors i.e customer churn
__DATA UNDERSTANDING__
RangeIndex: 3333 entries, 0 to 3332
Data columns (total 21 columns):
 #   Column                  Non-Null Count  Dtype  
---  ------                  --------------  -----  
 0   state                   3333 non-null   object 
 1   account length          3333 non-null   int64  
 2   area code               3333 non-null   int64  
 3   phone number            3333 non-null   object 
 4   international plan      3333 non-null   object 
 5   voice mail plan         3333 non-null   object 
 6   number vmail messages   3333 non-null   int64  
 7   total day minutes       3333 non-null   float64
 8   total day calls         3333 non-null   int64  
 9   total day charge        3333 non-null   float64
 10  total eve minutes       3333 non-null   float64
 11  total eve calls         3333 non-null   int64  
 12  total eve charge        3333 non-null   float64
 13  total night minutes     3333 non-null   float64
 14  total night calls       3333 non-null   int64  
 15  total night charge      3333 non-null   float64
 16  total intl minutes      3333 non-null   float64
 17  total intl calls        3333 non-null   int64  
 18  total intl charge       3333 non-null   float64
 19  customer service calls  3333 non-null   int64  
 20  churn                   3333 non-null   bool   
dtypes: bool(1), float64(8), int64(8), object(4)
__MODELLING__
Logistic regression, KNN, Random Forest
__EVALUATION & CONCLUSION__
Random Forest gave the best conclusion indicating which features were most important
