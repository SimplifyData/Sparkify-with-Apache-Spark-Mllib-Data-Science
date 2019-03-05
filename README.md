# Sparkify with Apache Spark Mllib & Data Science

Manipulate large and realistic datasets with Spark to engineer relevant features for predicting churn. 
Use Spark MLlib to build machine learning models with large datasets.

https://medium.com/@atif.zafar/7-critical-habits-of-music-service-subscribers-like-spotify-a126bd3201d2

### ** Purpose **

Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. 

Additionally, the ability to efficiently manipulate large datasets with Spark is one of the highest-demand skills in the field of data.

### ** Essential Skills **

1. Load large datasets into Spark and manipulate them using Spark SQL and Spark Dataframes

2. Use the machine learning APIs within Spark ML to build and tune models

3. Apply Data Science techniques on the Spark data set


### ** Overview **

Sparkify is a cloud music streaming service just like Spotify or Pandora. 

We are working on the data team of Sparkify. Million of users play songs here using free and premium service.
Users can upgrade or downgrade or cancel thier serivce. So they have to remain engage.
As a data scientist in this project I have to predict who will cancel the service (churn) before it happens to prevent millions of dollar in loss.

### ** Strategy **

We are provided the user log of the of the service.

The user log contains demographic information, user activities, timestamps, whether user is a paid or free tier, and etc. 

I have built a log and modeling to identify customers who are highly likely to quit using our service (Customer Churn). 

We can incorpoate the findings to launch a A/B test to build a recommendation engine to keep these users more engaged, and as well as pass them to the marketing team to engage these users with mails about thier favorite songs and offer them suscription discounts.

I have computed F1 scores to measure of model performance based on precision and recall. 

The F1 score will guide us to predict more precisely the users who are likely to churn, thus taking Sparkify towards growth.

### ** Results **

Random Forest Metrics:
Accuracy: 0.7755102040816326
F-1 Score:0.6774571897724607

### ** Conclusion **

The length of service used plays the most important factor to predict the churn rate. Subscription downgrade also indicates if the customer will churn. If the customer plays alot of artists and adds alots of songs in thier playlist then its a good sign. Lastly, songs played per session plays is also vital in predicting the churn rate.


### ** Data **

Customer User log

### ** Packages **

1. PySpark

2. Pandas

3. Seaborn 

4. Matplotlib

### ** Machine Learning Models **

1. Support Vector Machines

2. Random Forest Classifier

3. Gradient Boosted Trees

4. Logistic Regression

### ** Methodology **

1. Data Pipeline & ETL

2. Explortaory Data Analysis

3. Customer Churn

4. Feature Engineering

5. ML Modeling

6. Evaluating Models

7. Feature import analysis
