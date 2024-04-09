# Health-Insurance-Cost-Estimation-Project  
# Project Overview  
Healthcare costs can vary significantly based on individual characteristics and other factors. Understanding the determinants of health insurance costs can be valuable for insurance companies, policymakers, and individuals alike. By building a predictive model, we can provide insights into how different factors influence insurance costs and potentially assist in pricing strategies, risk assessment, and personalized healthcare planning.

# Project Structure  
The project is divided into the following sections:

- Data Understanding and Exploration: In this section, we load the dataset, explore the data by examining the first few rows, checking the shape and information of the dataset, and identifying null values.

- Data Cleaning: This section focuses on treating null values and dropping variables with a high percentage of missing values. We also handle outliers and multicollinearity among features.

- Data Preparation: Here, we perform univariate analysis to understand the distribution of data and prepare the dataset for modeling. This includes creating dummy variables for categorical features and scaling numerical features using MinMaxScaler.

- Model Building and Evaluation: In this final section, we split the data into training and testing sets, apply various regression models including Linear Regression, Ridge Regression, and Lasso Regression. We evaluate the models using performance metrics such as R-squared score, RSS, and RMSE. We also analyze feature importance and provide insights into model selection.
