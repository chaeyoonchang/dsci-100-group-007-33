# dsci-100-project_template

## Introduction

Tennis is a popular sport with a long history of competitive tournaments and rankings. A player's ranking is an essential metric used to evaluate their performance and overall skill level. While several factors can impact a player's ranking, such as age, seasons played, current rank, and prize money, it can be challenging to determine the best approach for predicting a player's best rank accurately.

In this proposal, we aim to predict a tennis player's best rank based on their age, seasons played, current rank, and prize money. We plan to use K-nearest neighbor regression, a machine learning algorithm, to analyze the data and make predictions. The goal of this project is to determine whether these variables have a direct or indirect impact on a player's best rank and which ones are most influential in making accurate predictions.

To accomplish this, we will use a dataset containing information on various tennis players, including their age, best rank, prize money, current rank, and seasons played. We will use five-fold cross-validation to estimate the smallest error in our model and then evaluate the optimal parameter value using the standard testing dataset. By analyzing the data and using visualization techniques such as scatter plots, we hope to gain valuable insights into the factors that influence a player's ranking in tennis.

## Predicting a Tennis Player's Best Rank Based on Their Age, Seasons Played, Current Rank, and Prize Money

 For our project we chose the columns Age, Best Rank, Prize Money, Current Rank, and Seasons. We are trying to predict the Best Rank using the other 4 variables. These predictors were selected because they contain the most data compared to other columns which mostly contain N/As. The choice of predictors was also based on their relevance to predicting a player's Best Rank. Variables such as Age, Best Rank, Prize Money, Current Rank, and Seasons were selected as they have a direct or indirect impact on a player's performance and ranking. Other variables such as Nicknames or Web Site were deemed irrelevant as they are not likely to have a significant influence on a player's ranking.

### Methods

We plan on Using K-nearest neighbor regression since all of the variables we selected are quantitative. We will have to standardize the data and determine the number of neighbors depending on the smallest estimated error which we will determine from the five fold cross validation from our tennis_data_train dataset. We will evaluate the optimal parameter value for our model by using the standard testing dataset to calculate the standard error, we will do this to all of our variables to ensure we have sufficient amount of predictors.

We will use similar scatter plots as the ones above with our standardized data, the predictors will be on the x-axis of their individual plot and the predicted Best Rank will be on the y-axis.

### References

"Player Stats for Top 500 Players" from: 
 https://www.ultimatetennisstatistics.com/

