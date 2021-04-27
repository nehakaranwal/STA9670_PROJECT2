# STA9670_PROJECT2
YELP Dataset Analysis
# Analyzing 10Gb of Yelp Reviews Data

I have used PySpark on AWS EMR to analyze 10Gb of Yelp review data. Yelp review data is sourced from Kaggle in json format and transfered to a public S3 bucket for analysis in the application s3://sta9760-spark-s3-dataset/yelp/
I look at some descriptive properties of the review data and analyze whether reviews tend to be optimistic or pessimistic.


## [Analysis](https://github.com/nehakaranwal/STA9670_PROJECT2/project02/Analysis.ipynb)


My Yelp source file:

Business:
s3://sta9760-spark-s3-dataset/yelp/yelp_academic_dataset_business.json

Review:
s3://sta9760-spark-s3-dataset/yelp/yelp_academic_dataset_review.json

User:
s3://sta9760-spark-s3-dataset/yelp/yelp_academic_dataset_user.json



## Cluster and Notebook Configs

![notebook](/assets/notebook_configuration.png)
![cluster](/assets/cluster_configuration.png)
