#  Supervised Machine Learning Regression Model for Medical Insurance Data

**Business Understanding**
The business under review is a Medical insurance company which is faced with the challenge of proper estimation of medical expenses that is caused by the diverse health conditions of its payees as some conditions are more common within some segments of its population. The objective of this business is to accurately forecast the medical expenses of its payees so that the right annual premium can be collected based on their health conditions. The aim here is to answer three major business questions which are: 
•	How does the smoking lifestyle of an individual affect the cost of their healthcare
•	Does the number of Children covered by health individual affect their Medical expenses?
•	How accurately can the given factors estimate an individual’s medical expenses?


**Data Understanding** 
the dataset to be analysed is a CSV file of medical insurance dataset alongside the application of the CRISP-DM methodology while the tool being used for this task is the Python’s Jupyter Notebook because of its ease of use and simplicity. The goal of this analysis is to build a prediction model to predict with an acceptable level of accuracy, the medical cost for individuals based on their Age, BMI, number of children covered, if Smoking or not and their Region of domiciliation in the US. 
The medical insurance dataset has 1338 observations, 6 predictors which are the age, bmi, children, smoker_yes, smoker_no, and region and one dependent variable – medical cost. This is a supervised machine learning task because the target variable to be predicted is being provided which is medical cost (y label) and the best use in this analysis is the linear regression because the outcome is a numerical and a continuous variable. In this analysis, the correlation between each predictor and the medical cost would be studied, the correlation analysis would be used to select 3 best predictors to build a simple linear regression model for each predictor. The performance of the R2 would be evaluated and hypothesis testing would be used to evaluate the statistical significance of the results. Two multivariate regression models would be built using the three best predictors and all the predictors in the dataset with the dataset, then the two models would be compared and evaluated. The Polynomial regression would be applied and the result would be evaluated in terms of performance improvement.

The codes have been attached as ipnb files in the code section.
