# Kaggle Hourse Prices: Advanced regression Techniques
This was performed as a final project for a graduate-level R class. Another student and I worked together to place as high as possible on the leader board, which had been open for a couple of years at the time of our attempt. The professor had six classes before us perform this same competition. The best score he had seen in any of the six classes was about 12.6. Our top reported Kaggle score was .11427 and placed us at 308 on the Kaggle leader board. By removing outliers, filling NA values, and creating a few new pieces of information by combining variables, we were able to boost our results. One of these created variables was ranked as the most important variable for all the models except one, and other variables that we created had a significant impact on model performance. Then we transformed our data sets into dummy variables of 0s and 1s but did not remove variables with near-zero variance. We used a combination of five models to predict house prices. From these models, we were able to create a linear average of them to use as our prediction. By trial and error, we were able to refine each of the models to fit the data closely and, using the Caret package, combine them, which had a synergetic effect. We learned an incredible amount about R and the importance of the caret package and how to implement at least nine very different algorithms. This exercise was a very positive experience.


### For more details view our final RMarkdown presentation in [PDF](https://github.com/jcoopa/Kaggle-Hourse-Prices--Advanced-regression-Techniques/blob/master/Kaggle%20Housing%20Prices%20Final%20Report%20Nov%2C%202019.pdf)

### Visit Kaggles Website: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## Data
### Two data sets provided by Kaggle
[Test Data](https://github.com/jcoopa/Kaggle-House-Prices--Advanced-Regression-Techniques/blob/master/test.csv)
[Train Data](https://github.com/jcoopa/Kaggle-House-Prices--Advanced-Regression-Techniques/blob/master/train.csv)

## Clean Data
### Extensive cleaning and preparation was performed on both the test data and the train data. 
[Data Preparation](https://github.com/jcoopa/Kaggle-House-Prices--Advanced-Regression-Techniques/blob/master/Home_Prices_Clean.TransformData.2019.Rmd)

## Analysis
### We used a blended model of 5 advanced machine learning techniques which provided a very desirable result. Over 17 techniques where tested during development. 
 * glmboost
 * glmnet
 * svmLinear
 * svmRadial
 * xgbTree
[Analysis](https://github.com/jcoopa/Kaggle-House-Prices--Advanced-Regression-Techniques/blob/master/Home_Prices_BlendedModel.2019.Rmd)
