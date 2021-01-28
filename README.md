# Exploratory Data analysis on reviews of Amazon products from Fashion, Beauty and Appliance categories.

This is one of the the capstone projects for the 6th Data Science Cohort of <a href="https://www.aisaturdayslagos.com/" target="_blank">AI saturdays Lagos</a>. Check their Githb [here](https://github.com/AISaturdaysLagos).


## Project Overview
Amazon is an e-commerce company where people buy and sell product from various categories. Customers can give feedback on the products they buy through reviews. This project aims to perform Exploratory Data Analysis (EDA) on reviews of products purchased from Amazon in the following categories;
* Fashion
* Beauty             
* Appliances


## The Dataset
The raw data used for this project can be found [here](https://nijianmo.github.io/amazon/index.html).
The data for each category was extracted as JSON files and converted into respective CSV files using the `pandas` library.
- [Amazon_Fashion.csv](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/Amazon_Fashio.csv)
    - ..rows, ..columns
- [beauty_csv](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/beauty.csv)
    - 5269 rows, 11 columns
- [appliances_csv](https://github.com/ahmadbashorun/AI6-amazon-reviews-EDA-project/blob/main/appliances.csv)
    - ..rows, ..columns
 
The columns or fields in the data are:
- `overall`, renamed to `productRating` is the rating of the product
- `verified`  
- `reviewerID` is the ID of the reviewer
- `reviewTime` is the date of the review
- `reviewerID` is the ID of the reviewer
- `asin`, renamed to `productID` is the ID of the product
- `reviewerName` is the name of the reviewer
- `reviewText` is the text of the review
- `size` is the size of the product






