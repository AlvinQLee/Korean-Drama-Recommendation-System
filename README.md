# Project Goal
The goal of this project is to understand the Graduate Admissions dataset, gain some insights from it, and finally to train a model that can predict the chances of graduate admissions.
![](images/graduate.jpg)

# Data & Images Source
Mohan S Acharya, Asfia Armaan, Aneeta S Antony : A Comparison of Regression Models for Prediction of Graduate Admissions, IEEE International Conference on Computational Intelligence in Data Science 2019. 
(from kaggle: https://www.kaggle.com/fernandol/countries-of-the-world)

Header image source: https://graduate.lclark.edu/

# Data Description
This dataset has 500 rows and 9 columns. Each row represents a graduate school applicant. Each column represents a different aspect or measure of the admissions prediction.

# Conclusion
3 different learning regressors (Linear Regression, Random Forest, and Gradiant Boosting) were tested, and we have acheived the best prediction performance using Linear Regression, followed by Gradiant Boosting, and then Random Forest.

![](images/predictions.png)

The best prediction performance was acheived using Linear Regression, using all features in the dataset, and resulted in the following metrics:  
  
MAE: 0.04396863063294708  
RMSE: 0.06136605787480696  
R2_Score: 0.7767101021347025  

Note that the Chance to Admit values in the dataset ranges from 0.34 to 0.97.
