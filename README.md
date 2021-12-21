# logistic_regression by sklearn
---
This repo contains informations about logistic_regression by sklearn

## configuration instructions

General Languages and versions

    •	Python version: 3.10.0
    •	Sklearn version: 1.0.1

If you do not have sklearn packages then execute the sentence to install sklearn

    pip3 install -U scikit-learn
    

## operating instructions
### My codes
In my codes I make classification with Scikit Learn Library to used logistic regression.
There are some pictures which are quantized to 256 grey levels and stored as unsigned 8-bit integers.
The loader convert these to float values on the interval [0, 1] which are eaiser to work with for many algorithms.
You can understand by seeing under picture.
![difference linear regression and logistic regression](https://rajputhimanshu.files.wordpress.com/2018/03/linear_vs_logistic_regression.jpg)
##### Logistic Regression is a Machine Learning classification algorithm that is used to predict the probability of a categorical dependent variable. In logistic regression, the dependent variable is a binary variable that contains data coded as 1 (yes, success, etc.) or 0 (no, failure, etc.)

   ### Logistic regression object in scikit learn has the following hyper parameters
    •penalty='l2',
    •dual=False,
    •tol=0.0001,
    •C=1.0,
    •fit_intercept=True,
    •intercept_scaling=1,
    •class_weight=None,
    •random_state=None,
    •solver='lbfgs',
    •max_iter=100,
    •multi_class='auto',
    •verbose=0,
    •warm_start=False,
    •n_jobs=None,
    •l1_ratio=None,
                    
   ### my parameters
    •penalty='l2',
    •dual=False,
    •tol=0.0001,
    •C=1.21,   // changed
    •fit_intercept=True,
    •intercept_scaling=1,
    •class_weight=None,
    •random_state=0,    //changed
    •solver='lbfgs',
    •max_iter=200,   // changed
    •multi_class='auto',
    •verbose=0,
    •warm_start=False,
    •n_jobs=None,
    •l1_ratio=None,

## copyright and licensing information

In my codes there's some pictures which are offered by AT&T Laboratories Cambridge.

## contact information for the distributor or author

minwoos0204@naver.com


