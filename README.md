# Credit-Fraud-Assessment

**Tech Stack:** AI/ML, Pandas, Numpy, Seaborn, SkLearn, Matplotlib, Linear Regression, Random Forest Regression,  K-Nearest Neighbours Regression, LGBM Classifier, Random Forest Classifier

<br /> 

**Dataset Description:** A total of 32582 data points for Credit Fraud Assessment are used with 14 variables including age, income, home ownership status, employment length, loan intent, loan grade, etc. The target variable is loan status which has 1 for loan approved and 0 for loan not approved. 

<br /> 

**Data Cleaning and Training**
- Finding and dropping duplicates
- Removing redundant values
- Removing absurd values
- Managing missing values
  - Iterative Imputing 
  - Standard Scaling

Following the train-test split, randomized search using the following is done to find the most optimal set of paraments. 
- LGBM Classifier
- Random Forest Classifier
- Linear Regression
- Random Forest Regression
- K-Nearest Neighbours Regression

<br /> 


**Learning Curve:** Learning Curve is then made for accuracy assessment. There is a high variance to be found. The model is then rebuilt with less complexity using just the random forest classifier and pruned decision trees to reduce overfitting. 





  
