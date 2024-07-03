# CIND820Project
Estimation of Obesity levels

# Data Files of the Project in CSV format
[**Original dataset file**](https://github.com/Sandia-Kumari/CIND820Project/blob/main/Original_ObesityDataSet.csv) is a Original Obesity dataset obtained from [**UCI repository**](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition) with Target variable 
[**Train dataset file**](https://github.com/Sandia-Kumari/CIND820Project/blob/main/train.csv) is a training dataset obtained from Kaggle with Target variable
[**Test dataset file**](https://github.com/Sandia-Kumari/CIND820Project/blob/main/test.csv) is a testing dataset obtained from Kaggle without Target variable 

# EDA Files of the Project in HTML and Python 
* [**ObesityData_Report_train1.html**](https://github.com/Sandia-Kumari/CIND820Project/blob/main/ObesityData_Report_train1.html) is the auto-generated EDA using Ydata Profiling for the Train dataset
* [**ObesityData_Report_test1.html**](https://github.com/Sandia-Kumari/CIND820Project/blob/main/ObesityData_Report_test1.html) is the auto-generated EDA using Ydata Profiling for the Test dataset
* [**Original_ObesityData_Report.html**](https://github.com/Sandia-Kumari/CIND820Project/blob/main/Original_ObesityData_Report.html) is the auto-generated EDA using Ydata Profiling for the Original dataset
* [**EDA.ipynb**](https://github.com/Sandia-Kumari/CIND820Project/blob/main/EDA.ipynb) is the detailed exploratory data analysis done by me using python different libraries, it includes descriptive statistics and some inferential statistics like correlation Analysis (Pearson), ANOVA and Chi-square test. It also includes data cleaning/pre-processing.

# Research Objectives of this Projecet
 1)	Is it possible to make predictions by using the original dataset (2111 observations) for training and new dataset (20758) for testing the model?
To answer this question I'll go through the following steps
* Data Loading
* Data Cleaning
* Data Preprocessing
* Model Selection
* Model Training
* Model Evaluation

Diverse classifiers will be used for this including 
* Logistic Regression
* Random Forest
* Support Vector Machine
      
 2)	To check whether the approached defined in Q1 is valid or not?
For that I will use performance metrics such as accuracy, recall, F1 score and confusion matrix as well as statistical testing including paired t-test and wilcoxon signed rank test to determine of there are significiant differences in perfomance between classifiers.


