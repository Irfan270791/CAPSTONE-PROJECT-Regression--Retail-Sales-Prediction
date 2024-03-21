# CAPSTONE-PROJECT-Regression--Retail-Sales-Prediction

Retail Sales Prediction - Rossmann Stores
In the fast-paced world of retail, having the ability to predict sales is of paramount importance. The project titled Retail Sales Prediction dives deep into the mechanics of predicting sales amounts for Rossmann Stores up to six weeks in advance.

📊 Exploratory Data Analysis (EDA)
Before diving into the models, it's crucial to understand the nuances of the dataset. Here are the key findings from the EDA:

Seasonal Variation: The sales data revealed that the business experiences a seasonal fluctuation, especially during the holiday season. This indicates a need for strategies to stimulate demand during non-peak seasons.
Competition: Areas with higher competition witnessed better sales. This insight can be used while selecting Store locations and where to focus marketing strategies.
Promotions: As expected, promotional periods give a substantial boost to sales. This underlines the importance of strategic planning around promotions.
Store Type and Assortment: Not all store types and assortments are made equal. Store type 'b' and assortment type 'c' lead the race in terms of sales.
Sales Volume Trend: A positive trend in sales volume indicates a growing business and a rising number of sales transactions.
🧮 Model Implementation and Evaluation
The project employed a series of regression models, including Decision Tree Regression, Random Forest Regression, Gradient Boosting Regression, and notably, the XGBoost Regression.

Model insights include:

In the preliminary model assessments, the Random Forest Regressor emerged as a frontrunner, registering an R-squared value of 0.88 on the validation set.
Subsequent hyperparameter optimization elevated the XGBoost model, which achieved an R-squared value of 0.94 on the validation set.
Notably, XGBoost consistently performed well, reflecting an R-squared value of 0.88 on the test data.


🔍 Conclusion: The comprehensive analysis and evaluation determined that the XGBoost Regression model is most adept at forecasting sales for Rossmann Stores.

🎉 Final Remarks
Through analysis and model evaluation, this project provides a robust predictive framework for retail sales. XGBoost Regression, in particular, has proven its efficacy, offering Rossmann Stores a potent tool for strategic planning and decision-making.
