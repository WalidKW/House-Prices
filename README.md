# House Prices EDA

![AI Student](https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png)

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

# Requirements:

- Perform Exploratory Data Analysis
- Data Cleaning
- Plot relationship between variables.
- implement machine learning models.

# Conclusion:

In this analysis, we explored a comprehensive dataset containing 79 explanatory variables describing residential homes in Ames, Iowa. Through various exploratory data analysis (EDA) techniques, we gained insights into the dataset and identified important features related to the sale price of houses.

During the EDA process, we examined the dataset's characteristics, such as the number of instances and features, data types, and descriptive statistics. By visualizing the correlations between variables using a heatmap, we discovered significant positive relationships between SalePrice and features like OverallQual, GrLivArea, and TotalBsmtSF.

Data cleaning was performed to handle missing values in the dataset. We identified the top three features with missing values as PoolQC, MiscFeature, and Alley. For features with missing values that could be replaced by a mean value, we imputed them accordingly. For other features, we used appropriate imputation techniques such as the most frequent value for categorical variables and the mean value for numerical variables. Data redundancy was not observed, indicating unique instances in the dataset.

To prepare the data for machine learning, we performed preprocessing steps. This involved extracting the features (X) and the target variable (y) from the dataset. We then normalized the features using StandardScaler and applied dimensionality reduction using PCA. The data was split into training and validation sets, with a test size of 20% and a training size of 80%.

Model selection was conducted using various regression models, including LinearRegression, DecisionTreeRegressor, RandomForestRegressor, SVR, MLPRegressor, and XGBRegressor. Evaluation metrics such as R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE) were used to assess the models' performance. Based on these metrics, the Random Forest Regressor and XGBoost Regressor showed relatively higher R-squared values, indicating better ability to explain the variance in the target variable. The Random Forest Regressor also exhibited lower MAE and RMSE values compared to the XGBoost Regressor. Therefore, the Random Forest Regressor may be considered the best model for this specific task. However, further analysis and validation using additional metrics and techniques are recommended to make a more comprehensive conclusion.

Additionally, cross-validation was performed to assess the models' generalization performance. The cross-validation scores for all models were plotted, providing an overview of their performance across different folds.

Overall, this analysis provides insights into the dataset, performs data cleaning and preprocessing, conducts model selection, and evaluates the models using various metrics. By combining these steps, we can make informed decisions and develop robust models for predicting house prices.
