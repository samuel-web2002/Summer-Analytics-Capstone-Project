# Summer-Analytics-Capstone-Project
## Introduction
This challenge is the capstone project of the Summer Analytics, a primer course on Data Science, conducted by Consulting and Analytics Club of IIT Guwahati in the summers.
The dataset is provided by DeltaX is the pioneering cross-channel digital advertising platform. The cloud-based platform leverages big data, user behavior
and machine learning algorithms to improve performance across the business funnel of advertisers.

### Problem Statement
Let's take a case where an advertiser on the platform (DeltaX) would like to estimate the performance of their campaign in the future.

Imagine it is the first day of March and you are given the past performance data of ads between 1st August to 28th Feb. You are now tasked to predict an ad's future performance (revenue) between March 1st and March 15th. Well, it is now time for you to put on your problem-solving hats and start playing with the data provided under the "data" section.

### Required Modules
* Numpy
* pandas
* Seaborn
* Matplotlib.pyplot
* tree
* GridSearchCV
* preprocessing
* r2_score, mean_squared_error
* Image, pydotplus

### Data Description
* date: the date on which the ad was made live
* campaign: campaign number
* adgroup: adgroup number
* ad: ad number
* impressions - Number of time the ad was shown
* clicks - Number of time the ad clicked shown
* cost - Amount spent to show ad
* conversions - Number of transactions received
* revenue: revenue generated from the ad

Our goal is to predict the revenue from Test data with a low RMSE score.

### Key Features
* Got RMSE value 106.65 for the Test Data
* Implemented Regression tree and optimized using GridSearchCv Algorithm, Code was clearly Documented.
* With Image Module we can clearly visualize tree, How it is divided, number of branches..etc
