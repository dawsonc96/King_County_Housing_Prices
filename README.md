# Prediciting the housing prices in King's County

![alt_text](https://static1.mansionglobal.com/production/media/article-images/cd824443d93a08dc613bc61adb52e4ae/large_GettyImages-9166149421.jpg?width=1260&height=708)

## Overview

The housing market is an especially important driver in our economy and is an alternative investment that many investors use to diversify their portfolios. Predicting the housing market is difficult as things like squarefootage, location, school district, distance to city, condition of home, etc. This project, we used regression analysis to to determine housing prices in King's County, Washington. We first used training data to explore feature building and feature inclusion, and then we built the final model using SciKit python library.

## Business Problem

Our residential and multifamily real estate firm is looking to expand into different markets on the west coast, and believes that King County, Washington is the next best market to move into. We specifically want to acurrately predict sales prices of houses in each neighbord. Having accurate predictions will give us a better idea of which neighborhoods to invest in.

## Approach 

To understand our market better, we brought in sale prices (as well as other features of the sale) of houses from 2014 and 2015 in King County, Washington. We first wanted to become familiar with the data and see which variables impacted price the most.

1. Cleaned data 
2. Created visualizations of variables that could have impact on price
3. Preformed tests to see which variables may be statistically significant to price
4. Engineered new variables that could help predict sales price of home.
5. Tested to see which variables were most important within our model.
6. Created final model with identifies features and implemented it on final data set.

We started off by seeing which variables correlated with one another and specifically looked at which variables correlated with price.

<p align="center">
 <img width="1100" height="700" src=Images/heatmap.png>
 </p>

We wanted to intially see the relationship between some of our independent variables and price. We first looked at waterfront and its affect on price. We found that waterfront has a statistically significant affect on price.

<p align="center">
 <img width="560" height="336" src=Images/waterfront_bar.png>
 </p>
 
 We were also interested in how the condition of the house affects the overall price. We found that the condition, which is on a 1 to 5 scale (1 being the worst condition and 5 being the best) has a statistically significant impact on price.
 
 <p align="center">
 <img width="560" height="336" src=Images/condition_bar.png>
 </p>

Lastly, we wanted to see if zipcode has any affect on price (as we would expect it would). We created a bargraph of the average price of the top 5 zipcodes in King County. We wanted to see if there was a difference between each zip code. We found that there was a significant relationship between zipcode and price, and would expect this across most zipcodes in King County, WA.

<p align="center">
 <img width="560" height="336" src=Images/condition_bar.png>
 </p>
