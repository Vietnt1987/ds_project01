
# How you choose homestay with correct price when traveling in Seattle with Airbnb data?
This investigation using database provided from link https://www.kaggle.com/airbnb/seattle/data
 
#1. Introduction.
When investigating homestay in Seattle, i’m most interested in checking price of homestay to know about all characteristics affected to the price. So, my questions are:
Which quatities affect to price and what is the most affected to price ?
How kind of neighbourhood group cleansed affected to price. which has the most price.
How kind of homestay affected to price. which has the most price.
How kind of room type affected to price. which has the most price.
In this investigation, i will use listings dataset. This data included 3818 and 92 columns included quantitical columns and categorical columns. For this huge of columns that make more difficult to statistic and maybe some columns not good for my investigation, i prefer to clone to new dataset with some columns which i feel will be good for my investigation.
To prepare data, i will read listings data, then create new dataset with expected columns. The data has missed values,so i will clean data by fill value or remove missed data. After that, i will convert datatype of price column to number.
Now we have new dataset look simple for analysis with only 12 columns. The first thing i look for overall this dataset.
 
There are many columns have missed value. I distinguish them to 2 types. One type is we can fill data and other is we can remove them. The first is for property_type, bathrooms, bedrooms, beds. Missed value is no information and it's not good for analysis. So i will remove it. The second is for columns: security_deposit, cleaning_fee, review_scores_rating. In this case we fill missed value with 0 because we can agree with security_deposit, cleaning_fee are free and review_scores_rate = 0.
#2. Which quatities affect to price and what is the most affected to price ?
Now, i will use heatmap chart to check correlation between quantitical variables.
 
Look at the headmap above we see that some properties affected to price are bathrooms, bedrooms, beds, guests_included. The most affected propery is bedrooms.
We will check correlation between most effected property, bedrooms with price.
 
As the chart, correlation between bedrooms with prices is linear. When bedrooms increases, price increases and vice verse.
#3. How kind of neighbourhood group cleansed affected to price. which has the most price?
Next we will check correlations between categorical variable with price.
 
The chart show that neighbourhood group = Magnolia has highest price.
#4. Section 3. How kind of homestay affected to price. which has the most price?
Draw correlation between Price and Property Type.
 
The chart show that homestay with property type = Boat has higest price.
#5. Section 4. How kind of room type affected to price. which has the most price?
Draw correlation between room type and price.
 
The chart show that room type = Entire home/apt has highest price.
#6. Conclusion.
Now we can conclude as following:
— The price of homestay in Seattle are affected by properties bathrooms, bedrooms, beds, guests_included. The most affected property is bedrooms. This variable correlates with price linear. When the bedrooms increases, it will lead to price increase.
— Homestay have neighbourhood_group_cleansed = Magnolia has the highest price
— Homestay have property type = boat has the highest price.
— Homestays have room type = Entire home/apt has the highest price.
