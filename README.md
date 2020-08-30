Project Overview: Sparkify is a digital music service similar to Netease Cloud Music or QQ Music. Many of the users stream their favorite songs in Sparkify service everyday, either using free tier that places advertisements in between the songs, or using the premium subscription model where they stream music as free, but pay a monthly flat rate. User can upgrade, downgrade or cancel their service at anytime.

Blog post for this project can be found at the link: https://medium.com/@chaturvedi.pankaj1984/capstone-project-on-sparkify-dataset-5088cc63e878

This is a Customer Churn Prediction Problem, Our job is deep mining the customers' data and implement appropriate model to predict customer churn as follow steps:

1. Clean data: fill the nan values , correct the data types, drop the outliers.
2. EDA: exploratory data to look features' distributions and correlation with key label (churn).
3. Feature engineering: extract and found customer-features and customer-behavior-features; Implement standscaler on numerical features.
4. Train and measure models: I choose logistic regression, linear svm classifier, decision tree and random forest classifier to train a baseline model and tuning a better model from best of them. It is worth mentioning that this data is unbalanced because of less churn customers, so we choose f1 score as a metrics to measure models' performance.


Libraries used: Pyspark, pandas, numpy, matplotlib, seaborn, sklearn

Motivation of the project:  Motivation behind this project is to understand the big data concept with Spark and as well as completion of data science nano degree program from Udacity.

Data Source: Data used was a small subset of the full Sparkify data made available by Udacity. The reason for this is that this project is run in a Jupyter notebook. To use the full dataset a cluster must be deployed on the cloud. Whilst this project utilises PySpark libraries, it does not utilize the clustering capabilities that Spark allows. A future addition onto this work may deploy a larger portion of the dataset, using a cluster.


Models used: All mdoels were developed using the PySpark ML library. 1. Logistic Regression 2. Decision Tree 3. Random Forest 4. Linear SVC

Model results: 1.Logistic Regression (F1 Score - 0.61) 2. Decision Tree (F1 Score - 0.52) 3. Random Forest (F1 Score - 0.47) 4. Linear SVC (F1 Score - 0.70)

Acknowledgement: Udacity
