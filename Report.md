## Abstract:
_-The goal of this project is to build a regression model to predict the prices of houses in the Kingdom of Saudi Arabia in the capital, Riyadh, due to the price disparity from one neighborhood to another. Also, Riyadh is considered one of the most densely populated cities in Saudi Arabia._
_The data was extracted by making a web scrape on the Aqar website, which is a site specializing in Saudi real estate, and feature engineering was done to improve the model and use several models to compare them._

## Design:
_-This project is based on creating a model capable of predicting house prices in the capital, Riyadh, and thus able to give the individual the appropriate price for the house based on several inputs. If people have good knowledge of the expected price of the house, they will not be deceived by the property owners._

## Data:
_-Two datasets were worked on:_
_main dataset This data was extracted from the Aqar website (price, Districts, n_bathroom, n_rooms, Size), but after Feature Engineering, 26 predictors, and the target variable (price). We have 11073 rows and 5 columns After cleaning the training set, the second dataset contains eight features (Price, Districts, Area, Front, Bedrooms, Salon, Street_width, Age), but after doing Feature Engineering, 56 predictors and one target variable (Price) were obtained, totaling 2084 observations._

## Algorithms:
*Feature Engineering:
-Simple EDA
-Adding polynomial terms
-Scaling input features
-Convert categorical features to numeric features using dummy variables 
-apply log for Price
*Models:
Linear Regression,Polynomial Regression,Ridge regression,Elastic net regularization ,Lasso(Least Absolute Shrinkage and Selection Operator)
*Model Selection:
In the beginning, the data was divided into 80 percent training data and 20 percent testing data. To train the model, we used the training data and did a cross-validation (K-fold CV) where K = 5 to compare several models and choose the best among them, then integrate the trained data and train it on the best model, and finally test the model using the test data that the model has not been trained on.
*The best model:
Linear Regression:
R2 Square->0.97808

## Tools:
_-Numpy and Pandas for Data Manipulation, Matplotlib and Seaborn for Data Visualization, sklearn(ElasticNet,Lasso,LinearRegression,Ridge)for model,sklearn(train_test_split,KFold)for model selection,sklearn(StandardScaler,PolynomialFeatures) for preprocessing, sklearn(metrics)for evaluation,Program: Jupyter Notebook._

## Communication:
_-Present a 5-minute slide presentation and a one-page report summarizing the project, beginning with an abstract and detailing the project, including the five major components. Also, my project will be included on my GitHub page._

