# Food Sales Predictions, What you need to know!
##In this analysis I demonstrate which goods at supermarkets were the most profitable, which supermarket types are the most successful, and develop a machine learning model to help you predict you're sales for your store based off of factors like item visibility, item types, and MRP

**Sean Rommes**: 

### Business problem:

How can we decide which items sell the best and what factors influence them? How can we use that information to predict how well we'll do in the future?


### Data:
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/


## Methods
- First I got an overview of the data and prepared it for cleaning. I checked for duplicates, missing values, unique values, and other inconsistinces in the data.
- Secondly I gathered the statistical values of the data for each of the columns I decided to keep for analysis.
- I created a histogram, boxplot, heatmap, and several line graphs to visualize and interpret data.
- I instantiated my machine learning models, presenting a linear regression model and a random forest and evaluated thier results, leaving you with a recommendation.

## Results

#### A histogram measuring item visibility, outlet sales, and mrp
![Screenshot (28)](https://user-images.githubusercontent.com/107956865/181852486-fd5b30d2-3551-4eae-8138-b884c44594c0.png)


> This histogram tells us the number of samples that occur in a category. For item visibility, most products were not allocated alot of space, under MRP there were more than 1200 samples that were priced between 100 and 125, under item sales the cheapest items were sold the most

#### A pair of line graphs to demonstrate product sales and which outlet types success
![Screenshot (30)](https://user-images.githubusercontent.com/107956865/181852992-95bdb0d2-34a3-4df5-8f78-503475c47b64.png)

> These line graphs tell us which products and outlet types had the most sales, which goods were the most popular, and also which outlet types sold the most products.
## Random Forests Model

My Random forest model was able to predict 93% of the available data using r2 scores and had a low high error variance based off of the root mean scores. 

## Recomendations
I would recomend our random forest model as it performed better on the r2 score with no tuning compared to our linear model which was also un-tuned. After some adjustments, i'm confident it can perform even better after some tuning!

## Limitations & Next Steps

For now the data is overfitted and requires tuning 


### For further information


For any additional questions, please contact **seanrommes@gmail.com**
