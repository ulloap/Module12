# Module12
nosql-challenge

## Installation
In order to successfully transfer the database to MongoDB Compass, I navigated to the location of the JSON through Terminal, and transfered it by inputting "mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json"

## Description
The mongoimport command on Jupyter was used in order to connect to MongoDB Compass. First I made sure my collection and document was in my Compass. A new restaurant was added as a document onto the collection, and edited to match the BusinessID to similar restaurant types. Afterwards, all restaurants in Dover Local Authority were deleted from the collection, and latitude and longitude were converted to decimals while "RatingValue" was converted to integers. Part 3 consisted of finding specific information and converting it to Pandas DataFrames, as well as use aggregations and pipelines in order to pull the required informaiton. 

## Credits
I used the original code given in order to format and properly follow along this module. Constant reference was made to the previous class examples in order to properly format my code. 
