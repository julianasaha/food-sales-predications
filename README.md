# Predicting Food Sales
Author: Juliana Sahagun
## Goal: The goal is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.

### Data:

1. Original/Up-to-date Source:
    * https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view
2. Source :
    * https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

### Methods
* Used libraries like seaborn and matplotlib to make visualizations for the data set.
* Used machine learning models to find model with the best recall sales prediction
  1.  LinearRegression
  2.  DecisionTreeRegressor
* Used simple imputation methods to handle the missing values in the data set.
* Preprocessed the data by scaling numerical information using the Scaler method and encoded categorical information using the OneHotEncoder method to help fit the model.
* Used Regression Metrics to evaluate the model's performance.

### Results
#### Visual 1 Item Popularity
![Bar chart popular items](https://user-images.githubusercontent.com/104885846/176869621-70f73ae6-5de1-458a-82c7-77e9af1bf4ac.png)
- The top three carried item types at these stores are 
1.   Fruit and Vegatables
2.   Snack Foods
3.   Household
#### Visual 2 Five Number Summary for Each Store
![image](https://user-images.githubusercontent.com/104885846/176869925-ca3c5967-8e06-4306-a682-bf37e54753b7.png)

- The boxplot indicates that Supermarket 'Type3' has the highest sales while 'Grocery Store' has the lowest.
#### Visual 3 Correlation Coefficients
![image](https://user-images.githubusercontent.com/104885846/176869814-0d9765ca-42f2-447b-8540-4fdb118f2672.png)

- The strongest correlation indicated in this graph is between 'Item_MRP' and 'Item_Outlet_Sales'while the weakest correlation is between 'Item_Visibility' and 'Item_Outlet_Sales'. Overall, there isn't any strong correlations, only moderate and low.
#### Visual 4 Visibilty Rate at Each Store
![image](https://user-images.githubusercontent.com/104885846/176920694-1ed1c574-76f4-4b20-8fb7-4e4b4ebf19f5.png)

- We can see here that 'Grocery Store' has a significantly higher percentage of display area although it is the store while the lowest sales. Havig a low percenatge of display area could be a factor when increasing food sales as it has worked for the other stores being compared.
#### Visual 5 Does the year of a store affect sales ?
![image](https://user-images.githubusercontent.com/104885846/176869774-17c99b0b-b61d-4bac-a368-047446d8ffa7.png)

- The two oldest outlets are 'Supermarket Type3' and 'Grocery Store'.
#### Machine learning Results:
-The regression tree model did the best with an R2 score of 60.4% which means that the model could account for 60.4% of the variation on the training data. The RMSE of 1082.66 indicates that the range of mean predicted values have a variance of $1,082.66 vs. actuals.

###### Recommendations:
From analyzing the data, we can conclude that the older type of outlets have a much lower visibility rate therefore, in order to increase sales rate I suggest increasing the visibility rate of different item types from most to least popular.  Also, the newer outlets can decrease the item maximum retail price in order to make more sales at lower prices like the older outlets do.
# For Further Information:
For any additional questions or concerns in regards to my sales predictions, please contact me at julianas4013@gmail.com. Thank you!
