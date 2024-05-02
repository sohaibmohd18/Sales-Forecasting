# Sales-Forecasting
## Description
This is a B2B sales prediction problem. The dataset available (includes a mix of synthetic and real data) is from a steel manufacturer that has other businesses in the Auto, Metal Fabrication, and Infrastructure as customers. The goal is to predict the quarterly sales to each of the 75 customers. In addition to the company-specific data, general economic indicators are also included that can be used for the purpose of prediction.

The goal is to predict the quarterly sales of various customers of a steel manufacturing company.

The final results are measured using Mean Absolute Error (MAE) evaluation metric.

## Environment
I have used Jupyter Notebook, you can use google colab as well.

## Key Features
**Data Preprocessing**: I have used comprehensive data preprocessing techniques like Data Cleansing, Handling Missing Values, Handling Outliers, and Handling Categorical Data.

**Data Visualization**: I have used box plot to visualize the outliers.

**Regression Model**: The model I have used here is the XGBoost Regression algorithm to get the accurate quarterly sales of the company.

**Evaluation Metrics**: The model's performance is measured using Mean Absolute Error.

## Data
The dataset contains the following files:

**EconomicIndicators.csv**: Supplemental economic information for the corresponding period in train/test data.

**train.csv**: The training dataset.

**test.csv**: The test dataset.

**sample_submission.csv**:  A sample submission file in the correct format.

## Columns

**train/test.csv**:

**ID** - Row id column

**Company** - Name of the company/customer

**Quarter** - Quarter for which the sales are provided/to be predicted

**QuickRatio** - Financial ratio indicating the customer's liquidity situation

**InventoryRatio** - Ratio of sales over inventory

**RevenueGrowth** - Revenue growth projections based on analyst and company projections

**MarketshareChange** - Market share growth projections based on analyst and company projections

**Bond rating** - Bond rating of company

**Stock rating** - Stock rating of company

**Region** - Region in which the company is situated or operates primarily

**Industry** - Industry are of company

**Sales** - Sales for the given quarter (target variable)

**EconomicIndicators.csv**:

**Month** - Month for which the indicators are provided

**Consumer Sentiment** - Consumer sentiment index value based on survey of consumers

**Interest Rate** - Average yield of 5 year US Treasury

**PMI** - Purchasing Managers Index

**Money Supply** - M2 Money supply

**NationalEAI** - National Economic Activity Index

**EastEAI, WestEAI, SouthEAI, NorthEAI** - Regional Economic Activity Index

## Contact
You can reach out to me on LinkedIn for any questions or feedback. Click on the LinkedIn Icon to land on my LinkedIn Profile.

[![LinkedIn](https://i.stack.imgur.com/gVE0j.png)](https://www.linkedin.com/in/sohaib-ahmed-mohammed)
