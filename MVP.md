
# Aqar

_Due to the information gap about house prices and the difference in house prices from one neighborhood to another, the individual may face a problem estimating house prices and may be subject to deception by real estate owners._
_Therefore, we will build a model that predicts house prices in various neighborhoods in Saudi Arabia's capital Riyadh based on several features . Which are a Price of house , size of house , number of rooms , number of bathrooms and Districts . _
_In the beginning, we have to know the most expensive neighborhoods so that we can be sure later that the model is able to predict prices based on the given data._

![](https://github.com/jameela-masar/T5-SDAIA-Regrassion-Web-scraping/blob/main/Images/c11.png)

_As shown in the picture, the most expensive neighborhoods are :Al-hamra , Al-Aqiq , Al-malga and A-Narjes. And we solved the dummies and now the number of features is : 13868 rows and 27 columns._

![](https://github.com/jameela-masar/T5-SDAIA-Regrassion-Web-scraping/blob/main/Images/corr.png)

_As shown in the picture , there is high correlation between Price and size(Area) and between Price , neighborhood Al-hamra , as what we say above Al-hamra the most expensive neighborhood, and neighborhoods is the  most important feature that affects the price._
_We will make a CV to determine the best model for the project to predict the prices of houses in different neighborhoods of  Riyadh city._
