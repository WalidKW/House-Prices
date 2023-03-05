# House Prices EDA

![AI Student](https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png)

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

# Requirements:

Perform Exploratory Data Analysis. This includes:

- Missing Values.
- Check if there is any redundant instances.
- Identify correlated features or the ones that highly correlated with the
label/outcome, if any.
- Plot relationship between variables.

# Conclusion:

In conclusion, the house price dataset contains a comprehensive set of 79 explanatory variables that describe various aspects of residential homes in Ames, Iowa. Through the use of exploratory data analysis (EDA) techniques such as general data analysis, missing values analysis, data redundancy analysis, and correlation analysis, I gained a better understanding of the dataset. The data consists of 1460 instances with 81 features. I also performed data description analysis, which provided information such as the mean and standard deviation of the dataset. The majority of the columns in the dataset were object and int64 types, with a few float64 types. By using the missingno library, I plotted the percentage of missing values in the dataset and identified the top three attributes with missing values (PoolQC, MiscFeature, and Alley). Data redundancy was not observed in the dataset, as all instances were unique. Through the use of a heat map for correlation analysis, I identified several variables that had a significant positive relationship with SalePrice, such as OverallQual, GrLivArea, and TotalBsmtSF. For further details on the instances,  [Data description](./data_description.txt).
