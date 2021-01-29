## Prediciting the housing prices in King's County

# Overview

The housing market is an especially important driver in our economy and is an alternative investment that many investors use to diversify their portfolios. Predicting the housing market is difficult as things like squarefootage, location, school district, distance to city, condition of home, etc. This project, we used regression analysis to to determine housing prices in King's County, Washington. We first used training data to explore feature building and feature inclusion, and then we built the final model using SciKit python library.

# Business Problem

Our residential and multifamily real estate firm is looking to expand into different markets on the west coast, and believes that King County, Washington is the next best market to move into. We specifically want to acurrately predict sales prices of houses in each neighbord. Having accurate predictions will give us a better idea of which neighborhoods to invest in.

# Approach 

To understand our market better, we brought in sale prices (as well as other features of the sale) of houses from 2014 and 2015 in King County, Washington. We first wanted to become familiar with the data and see which variables impacted price the most.

1. Cleaned data 
2. Created visualizations of variables that could have impact on price
3. Preformed tests to see which variables may be statistically significant to price
4. Engineered new variables that could help predict sales price of home.
5. Tested to see which variables were most important within our model.
6. Created final model with identifies features and implemented it on final data set.

bas




# Column Names and descriptions for Kings County Data Set
* **id** - unique ID for a house
* **date** - Date day house was sold
* **price** - Price is prediction target
* **bedrooms** - Number of bedrooms
* **bathrooms** - Number of bathrooms
* **sqft_living** - square footage of the home
* **sqft_lot** - square footage of the lot
* **floors** - Total floors (levels) in house
* **waterfront** - Whether house has a view to a waterfront
* **view** - Number of times house has been viewed
* **condition** - How good the condition is (overall)
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house (apart from basement)
* **sqft_basement** - square footage of the basement
* **yr_built** - Year when house was built
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip code in which house is located
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
