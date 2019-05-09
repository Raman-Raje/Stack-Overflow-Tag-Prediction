# Stack-Overflow-Tag-Prediction
Objective : To predict as many as tags possible with high Precision and Recall. 

Description: The dataset was obtained from kaggle. The given problem is multi-label classification problem. The dataset contains features such as Id, Title, Body and Tags. Data preprocessing and cleaning was done to remove html tags and hyperlinks. Micro-Averaged F1-Score was used as performance metric as mentioned on Kaggle.

Case Study Flow:
=================
1. Objective of this case study was to Suggest the tags based on the content that was there in the question posted on Stackoverflow.
2. The given dataset contains 6M data point in train with Id,Title,body and Tags as features.
3. EDA was done on tags and it is found that "c#", "java", "php", "asp.net", "javascript", "c++" are some of the most frequent tags.
4. On an avg. 2.88 tags were present perquestion.
5. We are considering only 5500 tags which covers 99.04 % of questions
6. Various machine learning models were tried and tested with OvR classifier to get the best results.
7. Logistic regression with TFIDF gave best accuracy of 0.0819 trained on 1M data pts.
8. Model accuracy degraded as we reduced the number of data points which is as expected
