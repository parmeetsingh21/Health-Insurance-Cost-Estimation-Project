# Health Insurance Cost Estimation Project
![health insurance](https://www.offthegridnews.com/wp-content/uploads/2013/03/HealthCareCosts.jpg)
## Project Overview  
Healthcare costs can vary significantly based on individual characteristics and other factors. Understanding the determinants of health insurance costs can be valuable for insurance companies, policymakers, and individuals alike. By building a predictive model, we can provide insights into how different factors influence insurance costs and potentially assist in pricing strategies, risk assessment, and personalized healthcare planning.

## Project Structure  
The project is divided into the following sections:

- Data Understanding and Exploration: In this section, we load the dataset, explore the data by examining the first few rows, checking the shape and information of the dataset, and identifying null values.

- Data Cleaning: This section focuses on treating null values and dropping variables with a high percentage of missing values. We also handle outliers and multicollinearity among features.

- Data Preparation: Here, we perform univariate analysis to understand the distribution of data and prepare the dataset for modeling. This includes creating dummy variables for categorical features and scaling numerical features using MinMaxScaler.

- Model Building and Evaluation: In this final section, we split the data into training and testing sets, apply various regression models including Linear Regression, Ridge Regression, and Lasso Regression. We evaluate the models using performance metrics such as R-squared score, RSS, and RMSE. We also analyze feature importance and provide insights into model selection.

## Files  
- Data.csv: The dataset containing Total Insurance cost.
- Health-Insurance-Cost-Estimation-Project.ipynb: Jupyter Notebook containing the Python code for the entire project.
- README.md: This README file providing an overview of the project.

## Libraries Used:  
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- How to Run

## To run the project:  
Ensure you have Python installed on your system.
Install the required libraries using pip install -r requirements.txt.
Open the Jupyter Notebook "Health-Insurance-Cost-Estimation-Project.ipynb".
Run the notebook cell by cell to execute the code and observe the results.  

## Conclusion:  
In conclusion, this project successfully developed a predictive model for estimating health insurance costs based on various individual attributes. By analyzing the dataset, cleaning the data, and preparing it for modeling, we were able to build robust predictive models using techniques such as linear regression and ridge regularization.

The performance evaluation of the models indicated high accuracy, with R-squared values of approximately 94.5% for both training and testing datasets. This suggests that the models capture a significant portion of the variance in the insurance costs, indicating their reliability in predicting future costs for new individuals.
