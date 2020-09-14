# Introduction 

# Data 

Wish.com is a popular e-commerice website. The dataset was uploaded in kaggle obtained from crawling from French wish website. More info is available @ https://www.kaggle.com/jmmvutu/summer-products-and-sales-in-ecommerce-wish.

## Project 

Project extends from preprocessing,  analysing the important feature columns, feature creations like per 1000 units sold, avg. customer ratings as target columns to using SMOTE for fabrication of target columns and random forest for prediction and GridSearchCV for optimization.

### EDA's

#### Origin of Products

![img](https://github.com/nibukdk/wish-ecommerce-analysis-prediction/blob/master/Imgs/country_origin_4_products.png)
Seems the products mostly originate from China.


#### Selling Prices Vs Discounts


![img](https://github.com/nibukdk/wish-ecommerce-analysis-prediction/blob/master/Imgs/prices_discounts_by_country.png)        

The graph, displpays that theres a heavy discounts on prodcuts from Venezuela as displayed by red line by avg of around 27 euros. 

Surprisingly, from the period of July,2020, when the data was taken, selling prices are higher than retail prices in countries like **Austria, GB and Singapore**. China where most of the product in the data is coming from is sold on average of around 8.5 euros with discounts on average of around 14 euros.

#### Relation of Discounts and Units Sold

![img](https://github.com/nibukdk/wish-ecommerce-analysis-prediction/blob/master/Imgs/Product_Sales_Per_1k.png)

Some important information like product's age on website, release date and so on are not available on data. Hence, assuming or ignoring those facts, it seems higher the discount price more likely is the sale of product to be higher. 

On average of 1000 (missing k's in xaxis were null, i.e no units sold in that range.), the avg, customer rating has not changed much, ranging around 3.8 mostly.

While as for price, item's sold from 50k-100k are cheaper  than lesser sold items on average by 2 euros.

