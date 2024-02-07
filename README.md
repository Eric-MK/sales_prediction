# Sales Forecasting Project Using Linear Regression
### Overview
This project involves creating a sales forecasting model using Linear Regression. The goal is to predict future monthly sales based on historical sales data. The process encompasses data preprocessing, feature engineering, scaling, model training, and evaluation, culminating in a visual comparison between actual and predicted sales.

### Dependencies
* [Python](https://www.python.org/)
* [Jupyter Notebook](https://jupyter.org/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [scikit-learn](https://scikit-learn.org/)
* [matplotlib](https://matplotlib.org/)

 

### Dataset
The California Housing dataset is a well-known dataset used in machine learning and statistics for predicting housing prices. In this project, the dataset is accessed and downloaded through the scikit-learn library, a Python library widely used for machine learning.

Specifically, we use the fetch_california_housing function from scikit-learn's datasets module. This function automatically downloads the dataset from a remote repository, making it easy to access and use for our analysis and model building.

The dataset contains data about different housing blocks in California, including:

* MedInc: median income in block
* HouseAge: median house age in block
* AveRooms: average number of rooms per household
* AveBedrms: average number of bedrooms per household
* Population: block population
* AveOccup: average number of household members
* Latitude: block latitude
* Longitude: block longitude
* **Target variable:** Median house value for California districts

### Usage
The project is contained in a Jupyter Notebook named *housing_price_prediction.ipynb*. This notebook includes the entire process: loading the dataset, preprocessing data, splitting it into training and testing sets, training a linear regression model, and evaluating its performance.

