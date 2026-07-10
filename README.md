# Used BMW Price Modeling - Regression & Diagnostics in R 
Explaining used car resale rices with a fully diagnosed, economically interpretable linear model. 

## Overview 
Using 10781 UK used BMW listings, this project builds a regression  odel go explain resale *price* from vehicle charactheristics (age, mileage, enginze size, fuel type, transmission, model line).The focus isnt't just predictive accuracy, it's building a model whose coefficients are *trustworthy enough to hand a pricing analyst*, which means taking classical regression assumptions seriously: testing for heteroschedasticity, normality, multicollinearity and autocorrelation at every stage, and being explicit about what remains unresold and why.  

## Dataset 
[**BMW Sales & Pricing Trends**](https://www.kaggle.com/datasets/ayeshaimran1619/bmw-sales-and-pricing-trends): This dataset, source from Kaggle, contains 10781 bmw cars and include 9 features. 

## Methodology 
Data loading -> Cleaning -> Preprocessing -> EDA -> Feature Engineering -> Model Building -> Diagnostics 
-> Model Improvement -> Variable Selection -> Outlier/Influence Analysis -> Evaluation -> Economic Interpretation

## Tools
-**R**: The programming language used for this project is *R*. The main packages used are *ggplot2* for data visualization, *corrplot* for correlation matrix, *rsample* for training the model, *patchwork* to arrange plots, *car* for vif. 



