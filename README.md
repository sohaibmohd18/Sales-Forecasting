# Sales-Forecasting
## Description
This is a B2B sales prediction problem. The dataset available (includes a mix of synthetic and real data) is from a steel manufacturer that has other businesses in the Auto, Metal Fabrication, and Infrastructure as customers. The goal is to predict the quarterly sales to each of the 75 customers. In addition to the company-specific data, general economic indicators are also included that can be used for the purpose of prediction.

The goal is to predict the quarterly sales of various customers of a steel manufacturing company.

The final results are based on the Mean Absolute Error (MAE)

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

InventoryRatio - Ratio of sales over inventory

RevenueGrowth - Revenue growth projections based on analyst and company projections

MarketshareChange - Market share growth projections based on analyst and company projections

Bond rating - Bond rating of company

Stock rating - Stock rating of company

Region - Region in which the company is situated or operates primarily

Industry - Industry are of company

Sales - Sales for the given quarter (target variable)


