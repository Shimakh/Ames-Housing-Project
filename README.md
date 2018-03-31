## Domain


The Ames Housing dataset was compiled by Dean De Cock for use in data science education


## Dataset 


The original data set contains 2930 observations and a large number of explanatory variables (23 


nominal, 23 ordinal, 14 


discrete, and 20 continuous) involved in assessing home values. Here we have only used 1451 observation.



The dataset describes the sale of individual residential property in Ames, Iowa from 2006 to 2010.



## Problem



The problem is to predict the final each home saleprice for the test dataset with the lowest possible 

error.


Using correlation and one hot encoding we find the most important variables. Then we try different models around those variable  

to see which one work the best. 


This data set provides an opportunity to compare the effectiveness of various modeling approaches for regression models.


## Solution


We use different models and the compare the result.


## Benchmark


A naive benchmark would be the the mean and the median of the sale price.


## Performance Metric


It is best to use F1 score as our performance metric. The F1 score conveys the balance between the 


precision and the recall.







