# Rocket-Recommender-System
This project aims to build a recommender system using data from the Rocket dataset. 

## 1. Data Loading and Preprocessing:
•	Loading Data: loading the 'events.csv', 'item_properties_part1.csv', and 'item_properties_part2.csv' files into pandas DataFrames.
•	Data Cleaning: The 'timestamp' column is converted to datetime objects. The item properties data is filtered to include only 'categoryid' and 'available' properties.
•	Data Exploration: exploring the dataset to understand customer behavior, product popularity, and purchase patterns.
## 2. Abnormal User Identification:
•	Defining Abnormal Behavior: The abnormal_user class is defined to identify users with unusually high event counts and transaction counts.
•	Identifying Abnormal Users:Identifying abnormal users based on the defined criteria.
•	Visualization: A scatter plot is used to visualize the relationship between event counts and transaction counts for abnormal users.
## 3. Exploratory Data Analysis (EDA):
•	Product Analysis: Analyzing product data to identify the most popular items in terms of views, additions to the cart, and transactions. Bar plots are used to visualize the results.
•	Customer Analysis: Analyzing customer behavior, including the number of unique visitors, customers who made purchases, and customers who only browsed.
•	Customer Behavior Analysis: Analyzing customer interactions with items, calculating time differences between views, cart additions, and transactions.
## 4. Feature Engineering:
•	Data Preparation: Preparing the data for modeling by creating a new DataFrame with features such as the number of items viewed, view count, bought count, and purchase status.
•	Calculating Rates: View rate and purchase rate are calculated and added as features.
•	Data Visualization: Pair plots and a correlation matrix are used to explore the relationships between features.
•	Data Cleaning: Missing values are handled using imputation.
## 5. Model Building and Evaluation:
•	Model Selection: exploring several regression models, including Linear Regression, Polynomial Regression, Random Forest, XGBRFRegressor, and a Neural Network.
•	Model Training and Evaluation: The models are trained and evaluated using R-squared as the evaluation metric.
•	Model Optimization: Grid search is used to optimize the hyperparameters of the Neural Network model.
## 6. Conclusion:
The project successfully built a recommender system using the Rocket dataset. The models were evaluated based on their R-squared values, with the Neural Network model achieving the highest score. Further improvements could be made by exploring different feature engineering techniques and model architectures.
