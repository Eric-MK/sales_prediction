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
The dataset consists of sales data, including dates and sales figures. The initial step involves converting the date information to a monthly period format to aggregate sales data on a monthly basis. This aggregation is crucial for analyzing sales trends over time.

### Data Preprocessing and Feature Engineering
* Converting Dates: Dates are converted to a monthly period format to facilitate the grouping of sales data by month.
* Monthly Sales Calculation: Sales data is aggregated by month to calculate total sales for each month.
* Sales Difference Calculation: The difference in sales between consecutive months (sales_diff) is computed to identify trends and seasonality, aiding in the model's ability to forecast future sales based on past changes.
* Feature Creation: Features are created by shifting the sales_diff values to represent sales differences from previous months. This step is essential for incorporating historical sales trends into the model.


### Model Preparation
* Scaling: The data is scaled using MinMaxScaler to normalize the features, improving the Linear Regression model's performance.
* Train-Test Split: The dataset is split into training and test sets to evaluate the model's performance on unseen data.

### Model Training and Evaluation
* Linear Regression Model: A Linear Regression model is trained on the scaled training data. The model aims to predict sales differences, which are then used to forecast actual sales figures.
* Model Evaluation: The model's performance is evaluated using metrics such as RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R^2 Score. These metrics provide insights into the model's accuracy and its ability to generalize to new data.

### Results Visualization
The project concludes with a visual comparison of actual vs. predicted sales. This visualization highlights the model's forecasting accuracy and offers valuable insights into its performance over the evaluated period.


