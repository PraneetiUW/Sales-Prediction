# Sales Data Analysis and Prediction

## Project Overview
This project focuses on analyzing and predicting sales based on historical data from a retail outlet. We employ several data preprocessing techniques, exploratory data analysis, visualization, and machine learning models to understand the factors influencing sales and predict future sales figures.

## Data Description
The dataset `data_sales.csv` includes the following columns:
- **Item_Identifier**: Unique product ID
- **Item_Weight**: Weight of product
- **Item_Fat_Content**: Whether the product is low fat or regular
- **Item_Visibility**: The % of total display area of all products in a store allocated to the particular product
- **Item_Type**: The category to which the product belongs
- **Item_MRP**: Maximum Retail Price (list price) of the product
- **Outlet_Identifier**: Unique store ID
- **Outlet_Establishment_Year**: The year in which store was established
- **Outlet_Size**: The size of the store in terms of ground area covered
- **Outlet_Location_Type**: The type of city in which the store is located
- **Outlet_Type**: Whether the outlet is just a grocery store or some sort of supermarket
- **Item_Outlet_Sales**: Sales of the product in the particular store. This is the outcome variable to be predicted.

## Data Cleaning and Preprocessing
Data cleaning steps include handling missing values, removing duplicates, and correcting data types. 

## Feature Engineering
Feature engineering involves creating new features that can potentially improve the model's performance. This includes:
- Extracting categories from `Item_Identifier`.
- Imputing missing values based on data distribution.
- Encoding categorical variables.

## Exploratory Data Analysis
 Includes distribution of variables, relationship between different features, and correlation analysis.

## Model Training and Evaluation
Several regression models are trained to predict sales:
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM

The models are evaluated based on R² and RMSE scores. Model training and evaluation steps are provided in `sales-Prediction.ipynb`.

## Results
The best performing model and its insights are discussed, along with key factors that impact sales.

