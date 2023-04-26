# House Price Prediction
> A project to predict the sale prices of houses based on various features.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project is aimed at predicting the sale prices of houses based on various features such as lot size, number of bedrooms and bathrooms, overall condition, garage area, and more. The dataset used is a collection of various features of houses and their corresponding sale prices.
- The project involves various stages such as data cleaning, data preprocessing, exploratory data analysis, feature selection, and model building.
- Data cleaning: The dataset contains a lot of missing values, and the notebook shows how to handle them by imputing missing values or dropping columns with too many missing values.
- Exploratory data analysis: The notebook explores the relationships between the target variable (SalePrice) and the features using visualizations and statistical analysis.
- Feature engineering: The notebook creates new features from existing ones, such as combining multiple categorical variables into a single variable or creating polynomial features to capture nonlinear relationships.
- Feature selection: The notebook uses various techniques, such as correlation analysis and recursive feature elimination, to select the most important features for the model.
- Model selection: The notebook evaluates several linear regression models, such as Ridge, Lasso, and ElasticNet, and selects the best one based on cross-validation scores.
- Model evaluation: The notebook evaluates the performance of the selected model on the test set using metrics such as mean squared error and R-squared.
- Model interpretation: The notebook examines the coefficients of the selected model and interprets them to gain insights into which features are most important in predicting house prices.
- Deployment: The notebook demonstrates how to use the selected model to make predictions on new data, and how to save the model for future use.
- Further improvements: The notebook suggests further improvements to the model, such as adding more features or using more advanced techniques like gradient boosting.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The LotFrontage and Garage Area features have a significant positive correlation with SalePrice.
- The MSZoning_RH and Exterior1st_CBlock features have a significant negative correlation with SalePrice.
- The features such as LotFrontage, BsmtFullBath, Overall Condition, MSZoning_RH, Overall quality, Exterior1st_CBlock, Garage Area, and CentralAir are significant in predicting the sale price of homes in Ames, Iowa.
- The Ridge regression model with alpha = 1.0 performed well in predicting the sale price of homes with an R-squared value of 0.913.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.9
- Pandas 1.3.4
- NumPy 1.20.3
- Scikit-learn 0.24.2
- Seaborn 0.11.2
- Matplotlib 3.4.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
-> This project was inspired by upgrad lessons



## Contact
Created by [@sreeprem](https://github.com/sreeprem) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
