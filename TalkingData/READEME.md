## TalkingData AdTracking Fraud Detection Challenge
Can you detect fraudulent click traffic for mobile app ads?

__地址：__ https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection#description

### 代码说明：
```xgb.py```: XGBoost方法  

#### 日志
2018-4-9
第一次提交：
```train_test_split(train, y, test_size=0.3, random_state=99)```  得分为：0.8235

第2次提交：
```'max_depth': 4```改成10，得分反而下降了，应该是过拟合了？ 得分下降为：0.8139

第3次提交：
xgboost包，提供了直接优化AUC的功能 ------设置：``` 'objective': 'rank:pairwise' ```, AUC值线下很高，线上Error.

2018-4-10
第4次提交：
```train_test_split(train, y, test_size=0.1, random_state=99)``` 改变test_size为0.1。 得分上升为：0.8352



