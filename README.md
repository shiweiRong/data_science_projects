# data_science_projects

## Movie Recommendation Engine Development in Apache Spark [link][1]

Developed a machine learning pipeline to generate personalized movie recommendations on the small MovieLens (100k) dataset. 
* Built data ETL and conducted online analysis processing (OLAP) (such as rating distribution wrt. movie category) using Spark SQL. 
* Implemented the alternative least square (ALS) model and selected the best model (RSME 0.59 on the training set and 0.88 on the test set) via grid search and 5-fold cross-validation. 
* Predicted personalized movie recommendations using user-based approaches and used locality-sensitive hashing (LHS) algorithm to find similar movies at scale. 




[1]:  https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4149976063988086/2093161739916212/2021872520586646/latest.html "ALS"
