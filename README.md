# Aberdeen-House-Price-Analysis

## Data Source
Data was scraped using Beeutifulsoup package from pages 1-40 of www.rightmove/Aberdeen.co.uk.

## Data Description
This dataset contains information including postcodes, amount of bedrooms and prices for 1000 properties in Aberdeen Scotland.
The data was cleaned and stored in a csv file.

## Project Aim
The aim of this project is to analyse property data in Aberdeen Scotland and build a model to predict price of property based on the area class and number of bedrooms. 

![Alt text](Properties_available.jpg?raw=true "Title")

![Alt text](Avg_price.jpg?raw=true "Title")

![Alt text](Std.jpg?raw=true "Title")

## Conclusion
Although the model is reasonably accurate at predicting property prices in Aberdeen there are still some outliers which are driving the model. 
The data shows that there are far more properties available in the cheaper areas than in the more expensive areas. 
Some of these properties contain four or more bedrooms which will greatly effect the mean price of the area. 
The data also only represents one day from the rightmove website which is constantly changing and so the model is likely to change everyday
