*Task 1: Implementing a Linear Regression Model for House Price Prediction*

*Overview:*

As part of my Machine Learning internship at Prodigy InfoTech, I worked on a machine learning task focused on predicting house prices using linear regression. The goal was to apply regression techniques to estimate house prices based on features such as square footage, bedrooms, and bathrooms.

*Objective:*

The primary objective of this task was to:
1. Load and prepare the dataset for analysis.
2. Clean the data by handling missing values.
3. Implement a linear regression model to predict house prices based on key features (square footage, bedrooms, and bathrooms).
4. Evaluate the model's performance using metrics such as Mean Squared Error (MSE) and R-squared.
5. Visualize the model's predictions and actual house prices to understand its accuracy.

*Key Features of the Task:*

1. *Data Loading and Inspection:*
   - The dataset was loaded using Pandas.
   - An initial inspection was performed to check for missing or incorrect values in columns such as square footage, bedrooms, bathrooms, and price.

2. *Data Preprocessing:*
   - Missing values were handled using the dropna() method, ensuring that the dataset was clean and ready for training.
   - The target variable was house price, and the predictor variables included square footage, number of bedrooms, and number of bathrooms.

3. *Model Implementation:*
   - I used the LinearRegression model from Scikit-Learn.
   - The dataset was split into training and testing sets using train_test_split().
   - The model was trained on the training set and used to predict house prices on the test set.

4. *Model Evaluation:*
   - Performance was evaluated using Mean Squared Error (MSE) to quantify the average squared difference between actual and predicted prices.
   - R-squared (R²) was used to assess how well the independent variables explained the variance in house prices.

5. *Data Visualization:*
   - After predictions were made, I visualized the results using scatter plots to compare actual versus predicted house prices.
   - The regression line and scatter plots provided insights into how well the model fit the data.

*Learning Outcomes:*

- Gained an understanding of linear regression and how to apply it to real-world data.
- Learned how to preprocess datasets by handling missing values.
- Developed skills in evaluating model performance using key metrics such as MSE and R-squared.
- Enhanced proficiency in visualizing regression results using Matplotlib to better interpret the model's predictions.

*Tools & Technologies:*

- *Python (Version 3.x)*: The programming language used for this task.
- *Pandas*: For data manipulation and preprocessing.
- *Scikit-Learn*: For implementing and evaluating the linear regression model.
- *Matplotlib*: For visualizing the actual vs. predicted house prices and plotting the regression line.

*Sample Output:*

The scatter plot comparing actual and predicted house prices gave a visual representation of how well the model performed. The regression line indicated the predicted trend, helping identify any discrepancies between the actual and predicted prices.
