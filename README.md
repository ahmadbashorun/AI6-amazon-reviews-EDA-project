# Exploratory Data analysis on reviews of Amazon products from Fashion, Beauty and Appliance categories.

This is one of the the capstone projects for the 6th Data Science Cohort of <a href="https://www.aisaturdayslagos.com/" target="_blank">AI saturdays Lagos</a>. Check their Githb [here](https://github.com/AISaturdaysLagos).


## Project Overview
Amazon is an e-commerce company where people buy and sell product from various categories. Customers can give feedback on the products they buy through reviews. This project aims to perform Exploratory Data Analysis (EDA) on reviews of products purchased from Amazon in the following categories;
* Fashion
* Beauty             
* Appliances


## The Dataset
The raw data used for this project can be found [here](https://nijianmo.github.io/amazon/index.html). 
The data for each category was extracted as JSON files and converted into respective CSV files using the `pandas` library. The full data extraction process is shown in this [notebook](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/Data%20extraction/Data_extraction.ipynb)
- [Amazon_Fashion.csv](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/Amazon_Fashio.csv)
    - 3176 rows, 10 columns
- [beauty_csv](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/beauty.csv)
    - 5269 rows, 11 columns
- [appliances_csv](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/appliances.csv)
    - 2277 rows, 8 columns
 
The columns or fields in the data are:
- `overall`, renamed to `productRating` is the rating of the product
- `verified`  
- `reviewerID` is the ID of the reviewer
- `reviewTime` is the date of the review (yyyy-mm-dd)
- `reviewerID` is the ID of the reviewer
- `asin`, renamed to `productID` is the ID of the product
- `reviewerName` is the name of the reviewer
- `reviewText` is the text of the review
- `size` is the size of the product


## Methodology
This project involves deriving meaningful insights from different fields in the data. The steps taken to arrive are these insights are:
- ### Importing relevant libraries: Some python libraries were imported to enable effective analysis of the data. They are: `pandas` and `numpy` for data cleaning and manipulation, `matplotib` and `seaborn` for visualisations, and; `textblob` for text processing.
- ### Simple sentiment analysis: Sentiment analysis was carried out on the reviews. The sentiments were labels as positive, negative and neutral reviews.
- ### Datetime analysis: The date from the `reviewTime` was used to get show trends in the reviews and other part of the data over a given period of time.
- ### Analysis on the products: Insights were derived from the products.
- ### Analysis on the reviewers: .The reviewers of the products were analysed. The data for each category was also [merged](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/Merged%20data.ipynb) to check if certain reviewers reviewed products from more than one category.
- ### Analysis on product ratings: The ratings of the products were between 1 and 5. These ratings were analysed and were also correlated to the amount of reviews as well as the sentiments.





The full code is contained in this [notebook](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/Exploratory-data-analysis.ipynb)




