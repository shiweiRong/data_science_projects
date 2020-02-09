# Data Science Projects

## Movie Recommendation Engine Development in Apache Spark [link][1]
Developed a machine learning pipeline to generate personalized movie recommendations on the small MovieLens (100k) dataset. 
* Built data ETL and conducted online analysis processing (OLAP) (such as rating distribution wrt. movie category) using Spark SQL. 
* Implemented the alternative least square (ALS) model and selected the best model (RSME 0.59 on the training set and 0.88 on the test set) via grid search and 5-fold cross-validation. 
* Predicted personalized movie recommendations using user-based approaches and used locality-sensitive hashing (LHS) algorithm to find similar movies at scale. 

## E-commerce Fraud Detection and Risk Analysis                                                                                          
Worked on 138K+ transaction data from an e-commerce company and developed machine learning models to identify whether the first transaction of a new user is fraudulent. 
* Performed exploratory data analysis and preprocessed data by removing duplicates, extracting new features from original data (such as time interval after signup and how many times a product is shared), encoding categorical features and handling imbalanced labeled data by SMOTE resampling after training/test splits. 
* Built logistic regression and random forest models, evaluated the models via 10-fold cross-validation and found optimal model parameters via grid search. 
* Selected the best model based on the F1 score (0.67) and designed a real-time alert system to prevent fraudulent activities. 

## Semantic Analysis for Youtube User Comments Dataset in Apache Spark                                                                        
Built machine learning models in Spark to classify users based on their comments on Youtube videos. 
* Preprocessed data by removing missing values and labeled part of users based on their comments. 
* Processed movie comments via RegexTokenizer and Word2Vec in SparkML. 
* Trained logistic regression, random forest and Gradient-Boosted Trees (GBTs) models and tuned hyper-parameters and selected the best model (ROC 0.955) based on 5-fold cross-validation. 
* Extracted features with term frequency-inverse document frequency (TF-IDF) approach and trained unsupervised model latent Dirichlet allocation (LDA) to obtain important topics of target users. 

## Sales Data Analysis and Demand Forecasting [link][3]
Worked on historical sales data and product information to develop a model to help a pharmacy store chain predict the future demand on different nutrition-related products. 
* Performed exploratory data analysis and preprocessed data by removing duplicates, extracting new features from original data, encoding categorical features and binning numerical features. 
* Built lasso regression (baseline) and random forest models for carry-over products (with historical sales data), evaluated the models via crossvalidation and found optimal model parameters via grid search. 
* Developed a similarity-based model for new products (without sales data) by comparing the cosine similarity between new products and carryover products. 

## Structured Streaming and Machine Learning for Credit Card Fraud Predictions in Apache Spark [link][4]                                        
Worked with a stream of transaction data to identify potential fraud hotspots in Apache Spark. 
* Performed PCA transformation to reduce the dimensionality of raw data transactions with correlated variables. 
* Built a machine learning pipeline with OneHotEncoder, VectorAssembler and Gradient-Boosted Trees (GBTs) using Spark MLlib. 
* Evaluated the model with precision, recall and F1 score on streaming data. 

[1]:  https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4149976063988086/2093161739916212/2021872520586646/latest.html "ALS"
[3]: https://colab.research.google.com/drive/1jOAkoe1rdKBhjgyeuWcqtzb2HItFM_5z
[4]: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4149976063988086/1393348256214161/2021872520586646/latest.html
