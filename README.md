# 记录参加的项目

## Kaggle项目

### 项目1. TalkingData AdTracking Fraud Detection Challenge

__Description:__  

Fraud risk is everywhere, but for companies that advertise online, click fraud can happen at an overwhelming volume, resulting in misleading click data and wasted money. Ad channels can drive up costs by simply clicking on the ad at a large scale. With over 1 billion smart mobile devices in active use every month, China is the largest mobile market in the world and therefore suffers from huge volumes of fradulent traffic.

TalkingData, China’s largest independent big data service platform, covers over 70% of active mobile devices nationwide. They handle 3 billion clicks per day, of which 90% are potentially fraudulent. Their current approach to prevent click fraud for app developers is to measure the journey of a user’s click across their portfolio, and flag IP addresses who produce lots of clicks, but never end up installing apps. With this information, they've built an IP blacklist and device blacklist.

While successful, they want to always be one step ahead of fraudsters and have turned to the Kaggle community for help in further developing their solution. In their 2nd competition with Kaggle, you’re challenged to build an algorithm that predicts whether a user will download an app after clicking a mobile app ad. To support your modeling, they have provided a generous dataset covering approximately 200 million clicks over 4 days!

__TimeLine:__ 
- April 30, 2018 - Entry deadline. You must accept the competition rules before this date in order to compete.
- April 30, 2018 - Team Merger deadline. This is the last day participants may join or merge teams.
- May 7, 2018 - Final submission deadline.
- All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. The competition organizers reserve the right to update the contest timeline if they deem it necessary.

__地址：__ https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection#description

---

### 项目2. Predicting Red Hat Business Value

__Description:__  

Like most companies, Red Hat is able to gather a great deal of information over time about the behavior of individuals who interact with them. They’re in search of better methods of using this behavioral data to predict which individuals they should approach—and even when and how to approach them.

In this competition, Kagglers are challenged to create a classification algorithm that accurately identifies which customers have the most potential business value for Red Hat based on their characteristics and activities.

With an improved prediction model in place, Red Hat will be able to more efficiently prioritize resources to generate more business and better serve their customers.

__TimeLine:__ 
- September 12, 2016 - First Submission deadline. A team must make at least one submission by this date in order to compete. 
- September 12, 2016 - Team Merger deadline. This is the last day competitors may join or merge teams.
- September 19, 2016 - Final submission deadline.
- All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. The competition organizers reserve the right to update the contest timeline if they deem it necessary.

__地址：__ https://www.kaggle.com/c/predicting-red-hat-business-value#description

--- 

## 项目3. House Prices: Advanced Regression Techniques

### Description: 
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad.
But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

__Practice Skills__
- Creative feature engineering 
- Advanced regression techniques like random forest and gradient boosting


### Evaluation
__Goal__  

It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

__Metric__ 
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

__Submission File Format__   
The file should contain a header and have the following format:
```
Id,SalePrice
1461,169000.1
1462,187724.1233
1463,175221
etc.
```

