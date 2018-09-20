# Alimama Internation Advertising Algorithm Competition(IJCAI-2018)
### 1. Introduction of the Project
This is a record of a CTR competition, Alimama Internation Advertising Algorithm Competition, host by Alimama, Alibaba in March to May 2018. The scenario is happened on TAOBAO, a ecommence website, where people search some items/keywords after landing on, and they may click some and maybe finally purchase. The main task here is to predict conversion rate/probability given each scenario(customer, shopper, item, context, etc.)

This is a small sample of the original scripts, for further and more knowledge of my solution, you can check my github at:https://github.com/jinwangjoshua/IJCAI_2018_Alimama_CTR/blob/master/Workflow.ipynb

### 2. Understanding and Cleaning
There are five dimensions of data was given: meta data, items' data, customers' data, shoppers'data, and context data. And in the train dataset, if conversion happened is given.

We build some rules to clean the original data, say duplicates records with instanceids. In this scripts, we use the cleaned data.

### 3. Feature Engineering
For better model building, we tried to find more usefel features based on our business sense. In addition to the raw features, we created extra features in five dimensions: statistic features, TopN features, time window and time difference features, interaction features and other features.

### 4. Model Training and Hyperparameter Tuning
We tried many machine learning models, also with the help of TPOT, a AutoML tool to help the model selection. And finally we find the GBDT transformers perform best.

In this scirpt, LightGBM model is applied and the pruning process is helped with hyperopt,a automatic hyperparameter optimization providing optimization algorithms like TPE searching and random searching.

### 5. Summary

### 5. Model Ensemble 
666

### 6. After-competition Summary 
666

### 7. Reference and Depedencies
666
- Linux 16.04
- Python3
- Pandas 0.19
- scikit-learn 0.19.1
- numpy 1.13
- TPOT 0.9.3 (Auto ML)
- hyperopt 0.1 (Automatic hyperparameter optimization)
- feature-selector

Team: Datababa
Member: Xiaoshuai Jin(me), Lucas Xu,  Akasi Shang

