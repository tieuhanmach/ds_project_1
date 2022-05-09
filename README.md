# **ds_project_1**

## **Motivation**

This project is used to answer my 3 question regarding Airbnb activity in Seattle, USA:
1. Which neighbourhood has the highest price and which one has the lowest price?
2. How characteristics of host impact house price?
3. Relationship between a propery's features with its price.

## **Libraries**
This project use built-in libraries for data wrangling, data visualization and data modeling:

`import pandas as pd`

`import numpy as np`

`import matplotlib.pyplot as plt`

`import seaborn as sns`

`from sklearn.linear_model import LinearRegression`

`from sklearn.model_selection import train_test_split`

`from sklearn.metrics import r2_score, mean_squared_error`

`import datetime`

`%matplotlib inline`

## **Table of content**
1. **data** contains data files that used in project
2. **Data Processing.ipynb** contains the code that I used to handle above data and come to conclusion

## Conclusion
After bunch of coding and analyzing, I come into bellow conclutions:
1. Neighbourhood: Most of the price is in range of $200, there are some outstanding value in the center of Seattle. There are more properities in the North than in the South
2. Host: Phone, email, review are the most frequent verification method that a host used. In contrast, manual online, sent_id and linkedint are the methods of highest price. 
3. Property's feature: 
- The most frequent amenities also relates to most expensive house price - elevator, gym, wheelchair accessible, doorman, pool.
- Dorm is the cheapest type and boat has an outstanding hight price compare with others.
- Entire home/apt is the most expensive room type, while tent-shared room and loft-shared room are the least expensive.
- There's not much difference in price between bed type in the same room type, but real bed is the most expensive bed type.

A blog post that contains conclusions from this project: https://seattlehouseprice.blogspot.com/2022/05/a-deep-dive-into-seattle-house-rent.html

