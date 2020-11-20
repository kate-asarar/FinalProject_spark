# Final Udacity Nano-degree Project
# Predicting Sparkify Churn


## Project description:

# Problem statement:

Churn is when a user chooses to cancel or downgrade a service. It can happen due to many reasons, the financial situation of the user, their needs for the service changing etc.
The churn rate that companies care about however, is the one caused directly related to their product. A user might opt to cancel a subscription because they cant find what they want, because the GUI design is bad and they keep having to visit the help page to understand what to do, or because they don't feel like they are getting a good deal on it. It is in these cases where being able to predict churn can make the biggest difference for a company. By offering a wider selection, updating their platform or even sending out groupons to the soon to churn users, they can keep the customers happy and retain their subscritptions for much longer.
Solution stategy and project description
In this project, a smaller set of data 128 Mb was given to experiment on. The project will go through the stages of CRISP-DM to analyze, transform, modelize and evaluate the created prediction models. The expected results of this project are data analysis as well as trained machine learning model that are able to classify a user as a churning user or one that will stay. 

## Requested libraries: 

- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [pyspark](https://spark.apache.org/docs/latest/api/python/index.html)
- [seaborn](https://seaborn.pydata.org/)

## files: 

The dataset used in this project is bigger than the 100 Mb allowence for github file and is therefore not included in the project. 
This repository contains the jupyter notebook Sparkify.ipynb, which is used to analyze and predict churn in a small user log data set as well as a README.md file. 

## Results: 

Conclusion
This projects aims at understanding and predicting churn in a small user dataset by using Apache Spark's analyrics engine and its powerful libraries.
The project goes through the different technical steps of the CRISP DM process starting with data understanding, followed by feature extraction, modeling and finally evaluation. 
 
Using the methods presented in this jupyter-notebook, and the best performing model which is the logistic reression classifier, we are able to correctly identify 85% of unhappy users and offer them discounts or rewards to keep their subscriptions. Furthermore, with the high precision score 94.5% achieved by the model , we are able to save money by avoiding giving out offers to already happy and staying customers.
Future work can include adding a location feature to include the influence of internet connection quality on churn as well as trying out other machine learning models such as Random Forest classifiers.
