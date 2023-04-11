# **Customer Conversion Prediction insurance**
<br/>

## **Project statement**
<br/>
In the Customer Conversion Prediction project, machine learning models are used to predict whether a client will subscribe to an insurance policy. The project aims to help the insurance company identify the customers most likely to convert. This is to make sure that they can be targeted by phone calls and that the costs associated with telephonic marketing can be reduced as well. In order to train and evaluate the performance of the machine learning models, historical sales data will be used as the basis for training and evaluating them. The analysis of the model will be done to identify the crucial factors contributing to the conversion. The performance of the model will be evaluated using the AUROC metric. 

### 1. Importing required libraries
### 2. Cleaning dataset
<br>
Cleaning missing value,duplicate,null values and data types

### 3.Exploratory data analysis
#### Target variable analysis

![target](https://user-images.githubusercontent.com/113424127/231206828-ccc1e59d-6441-481e-a555-54490c9c18c5.png)

#### Univariate analysis

![univariate](https://user-images.githubusercontent.com/113424127/231207242-7f82b642-14d4-4e7f-b60c-a1fd021c55ed.png)

#### Bivariate analysis

![bivariate](https://user-images.githubusercontent.com/113424127/231207377-d2242078-3abe-47e6-8830-31bd83fb06a8.png)

#### Correlation of data
![correlation](https://user-images.githubusercontent.com/113424127/231207551-3efc9b53-cbfc-4bf0-9254-ce47d2b221dd.png)

### 4.Encoding data
### 5.Train test split
### 6.Scaling data
### 7.Models
Logistic regression,random forest,xg-boost
### 8.Final model
XG-Boost
#### AUROC Plot
![roc](https://user-images.githubusercontent.com/113424127/231208505-4dea7556-f746-4840-9422-214b53a3bf7a.png)
#### Feature importance

![feat_importance](https://user-images.githubusercontent.com/113424127/231208669-cfc273a5-91bb-4adb-93ab-d88c5d1db3cf.png)
ance

## Conclusion 
XG_boost outperformed all the other models with the highest AUROC score of 0.9241
<br/>
This implies that XG-boost is suitable to predict whether the client will subcribe to the insurance or not.



