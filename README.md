Overview
The goal of this competetion is to predict the quarterly sales to various customers of a steel manufacturing company.

Data about the companies is available in train.csv. Various economic indicators for the same period at a monthly level are available in EconomicIndicators.csv.
Description
This is a B2B sales prediction problem. The dataset available (includes a mix of synthetic and real data) is from a steel manufacturer that has other businesses in the Auto, Metal Fabrication and Infrastructure as customers. The goal is to predict the quarterly sales to each of the 75 customers. In addition to company specific data, general economic indicators are also included that can be used for the purposes of prediction.

Evaluation
The submissions will be evaluated using mean absolute error.

Submission File
For each ID in the test set, you must predict the sales for the company in the given quarter. The file should contain a header and have the following format:

ID,Sales
7,110
8,340
16,180
17, 500 etc.

Dataset Description
The dataset contains the following files

Files
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
EconomicIndicators.csv - supplemental economic information for the corresponding period in train/test data
Columns
Train/test.csv
ID - Row id column
Company - Name of the company/customer
Quarter - Quarter for which the sales are provided/to be predicted
QuickRatio - Financial ratio indicating the customer's liquidity situation
InventoryRatio - Ratio of sales over inventory
RevenueGrowth - Revenue growth projections based on analyst and company projections
MarketshareChange - Market share growth projections based on analyst and company projections
Bond rating - Bond rating of company
Stock rating - Stock rating of company
Region - Region in which the company is situated or operates primarily
Industry - Industry are of company
Sales - Sales for the given quarter (target variable)
EconomicIndicators.csv
Month - Month for which the indicators are provided
Consumer Sentiment - Consumer sentiment index value based on survey of consumers
Interest Rate - Average yield of 5 year US Treasury
PMI - Purchasing Managers Index
Money Supply - M2 Money supply
`NationalEAI' - National Economic Activity Index
EastEAI, WestEAI, SouthEAI, NorthEAI - Regional Economic Activity Index
