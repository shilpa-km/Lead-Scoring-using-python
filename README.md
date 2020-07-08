# Data Science- Lead Scoring-using-python :Project overview
* Created a tool to identify Lead scoring , An education company  sells online courses to  industry professionals.
* Once  leads are acquired, employees from the sales team start making calls, writing emails, etc. The company requires you to build a model wherein you need to assign a lead score to each of the leads such 
that the customers with higher lead score have a higher conversion chance
* Build a logistic regression model to assign a lead score ,we use Optimized Logistic  Regressors using GridsearchCV to reach the best model. 


# Code and Resources Used
**Python Version:** 3.7

**Packages:** pandas, numpy, sklearn, matplotlib, seaborn

# Data include 
* Prospect ID
* Lead Number
* Lead Origin
* Lead Source
* Do Not Email
* Do Not Call
* Converted
* TotalVisits	
* Total Time Spent on Website
* Page Views Per Visit	
* Last Activity
* Country	 etc

# Data Cleaning
Next process is need to clean the data so that it was usable for our model
* First we need to check  if there is any duplicates are there if so remove the duplicate
* we will drop the columns having more than 70% NA values.
* Now we will take care of null values in each column one by one.


# EDA

* so data is cleaned now we are moving to analytic part
* data analysis is done using Univariate Analysis
* From data analysis we can come to conclusion of various aspect i.e Total Time Spent on Website,TotalVisits.Page Views Per Visit ,etc	

# Model Building
* Converting some binary variables (Yes/No) to 1/0 ,For categorical variables with multiple levels, create dummy features (one-hot encoded)
* I also split the data into train and tests sets as 80 % go into the training test, 20% in the validation test
* we moveon to Feature Scaling
* I tried to build LogisticRegression Model

# Model performance
With the help of LogisticRegression Model we get an Accuracy of logistic regression classifier on test set: 0.93


