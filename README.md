Final Udacity Nano-degree Project: Predicting Sparkify Churn

Project description:

In this project, a smaller set of data 128 Mb was given to experiment on. Once all stages of cleaning, transforming, feature extraction, modeling and evaluating are ready, the scripts can be deployed to a AWS cluster to run on the 12 GB dataset stored in a AWS S3 bucket using Spark.

Requested libraries: 

- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

Dataset: 

The dataset used in this project is bigger than the 100 Mb allowence for github file and is therefore not included in the project. 


Results: 

The aim of this project is to understand and predict churn in a small user dataset, by using Apache Spark's analyrics engine and its powerful libraries.

The project goes through the different technical steps of the CRISP DM process starting with data understanding, followed by feature extraction, modeling and finally evaluation.

Using the methods presented in this jupyter-notebook, we are able to correctly identify 80.7% of unhappy users and offer them discounts or rewards to keep their subscriptions. Furthermore, with the high overall precision score achieved by the models 87.5 for logistic regression, we are able to save money by avoiding giving out offers to already happy and staying customers.
