# Google Play Store Apps Rating Prediction

This is a personal project using Kaggle's google play store data.

Dataset Info. : https://www.kaggle.com/lava18/google-play-store-apps?select=googleplaystore.csv

Work File : https://github.com/GullyMac/PlayStore/blob/master/playstore.ipynb

Report : https://github.com/GullyMac/PlayStore/blob/master/report.pdf

20.07.13 last edit

---

## 0. Environment

* Language : Python
* Editor : Google Colaboratory (Jupyter Notebook)

   ! Performance can change depending on the hardware allocated by Colab.
   
* CPU : Intel® Xeon®
* RAM : about 25GB
* Disk : about 68GB

---

## 1. Introduction

#### Background:

We can make the predictive model of the Google App Store apps' rating,

It can be used to predict changes in ratings when updating an app 

or to locate a specific app in the app market.

#### Metric: MAE, MSE

---

## 2. Data Set

#### Data Sets are provided by Lavanya Gupta in Kaggle

This work is licensed under the Creative Commons Attribution 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by/3.0/.

#### Response Variable

* Rating

#### Explanatory Variable

* App(name), Category, Reviews, Size, Installs, Type, Price, Content Rating, Genres, Last Updated, Current Ver, Android Ver

---

## 3. Library

#### Environment Setting

* google.colab.drive : mount at google drive
* warnings : ignore warning message
* os : directory setting

#### Data Manipulation

* pandas : data manipulation
* numpy : matrix operation
* math : numerical operation
* random : random number generation
* time : time measurement

#### Visualization

* matplotlib.pyplot : graph drawing
* seaborn : graph drawing

#### Modeling

* sklearn.model_selection.train_test_split : seperate train and validation data set
* sklearn.model_selection.KFold : k-fold cross validation
* sklearn.metrics : residual measurement
* bayes_opt : Bayesian optimization
* functools.partial : freeze function’s arguments
* sklearn.linear_model.LinearRegression : multivariate linear regression modeling
* lightgbm : lightGBM modeling
* keras : neural network modeling
