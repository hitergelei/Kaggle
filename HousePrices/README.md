##项目3. House Prices: Advanced Regression Techniques

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
