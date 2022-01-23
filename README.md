## This repository will hold all the pyspark related projects

## Sentiment Analysis using Pyspark (project-1)
For the first project. I will be using performing sentitment analysis using pyspark. The result will be tracked using mlflow using different algorithms like Logistic Regression and RandomForest. The best result achieved is 0.83 AUROC. Pretty good!

#### Data
- I will be using Sentiment140 from standford http://help.sentiment140.com/for-students/
- I have reduced the size by 8 times to reduce the training time


#### Data preparation
- pyspark inbuild pipeline 

#### Model training
- pyspark inbuild crossvalidation
- pyspark inbuild gridsearch
- pyspark inbuild machine learning models

#### Model Tracking
- MLFLOW
<p align="left">
<img src="assets/pySpark_mlflow.JPG" height="370px" width="370px">
<img src="assets/pySpark_sentiment_analysis.JPG" height="370px" width="370px">
<p>


## Customer churn (project-2)
For the second project, I will be creating a model to predict customer churn. I think this is a very interesting project as it will have direct impact on the company's business. If we are able to identify potential customer churn, actions can be taken to prevent that from happening


#### Data
The data contains all the "actions" taken by the user on the company's website. After aggregating, there are around 450 unique users and around 20% churn rate
The data have been taken from https://github.com/abduygur/churn-prediction-using-spark


#### Data preparation
I have followed alot of the transformation techniques used from below repository as the author have use many interesting feature engineering technique
https://github.com/abduygur/churn-prediction-using-spark


#### Model training
The evaluation metrics that was selected is recall as we want to "catch" all the potential customer churn
Best model (random forest) achieved a precision of 98~%


#### Summary
This is a interesting project for me as I was able to practice using pyspark for feature engineering and task like predicting customer churn have direct impact on the company's business