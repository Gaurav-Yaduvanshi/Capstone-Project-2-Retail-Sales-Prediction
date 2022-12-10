Retail-Sales-Prediction
480px-Rossmann_Logo svg

📖PROBLEM STATEMENT
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. My work includes various plots and graphs , visualizations , feature engineering , ensemble techniques , different ML algorithms with their respective parameter tuning , analysis and trends . Predictions are of 6 weeks of daily sales for 1,115 stores located across Germany.

📖ALGORITHMS USED:
I. Linear Regression
II. Regularization (Lasso and Ridge Regression)
III. Decision Tree
IV. Random Forest
📖Solution Strategy
My strategy to solve this challenge was:

Step 01: Data Description: Use statistics metrics to identify data distribuctions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

Step 08: Deploy Model to Production: Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.

📖CONCLUSION
In analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable, 'Sales' and also transformed it. Next we analysed categorical variable and replaced null values, we also analysed numerical variable, found out the correlation, distribution and their relationship with the dependent variable using corr() Function. We also removed some numerical features who had mostly 0 values and hot encoded the categorical variables.

Next we implemented six machine learning algorithms Linear Regression, lasso,ridge, decission tree, Random Forest. We did hyperparameter tuning into improve our model performance.

1. The sales in the month of December is the highest sales among others.
2. The Sales is highest on Monday and start declining from Tuesday to Saturday and on Sunday Sales almost near to Zero.
3. Those Stores who takes participate in Promotion got their Sales increased.
4. Type of Store plays an important role in opening pattern of stores. All Type ‘b’ stores never closed except for refurbishment or other reason.
5. We can observe that most of the stores remain closed during State holidays. But it is interesting to note that the number of stores opened during School Holidays were more than that were opened during State Holidays.
6. The R Squared score of all Liner Regression Algorithm with or without Regularization are quit good which is 0.86.
7. the R Squared score of the Decision Tree Regressor model we got 0.97 on test set which is also good.
8. The Random Forest regressor model performed 0.98 which is very well amoung the others.
10. The random forest regressor model is our optimal model and can be deploy.
