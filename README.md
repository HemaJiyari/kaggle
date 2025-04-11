# 🧠 B2B Sales Forecasting – Steel Manufacturing Company

## 📘 Overview

The goal of this project is to **predict quarterly sales** for a steel manufacturing company that supplies to various B2B customers. This competition dataset includes both synthetic and real data from a steel manufacturer with clients across **Auto, Metal Fabrication, and Infrastructure** sectors.

In addition to customer-specific data, **macroeconomic indicators** are provided and can be leveraged to enhance sales predictions.

---

## 🏁 Objective

Develop a predictive model that estimates sales figures for each company in the test dataset for future quarters. The accuracy of the prediction will be evaluated using **Mean Absolute Error (MAE)**.

---

## 📂 Dataset Description

### 🔹 Main Files

| File Name              | Description                                      |
|------------------------|--------------------------------------------------|
| `train.csv`            | Historical sales data for training               |
| `test.csv`             | Data for which sales must be predicted           |
| `sample_submission.csv`| Sample format of submission                      |
| `EconomicIndicators.csv`| Economic data provided monthly                   |

### 🔹 train.csv / test.csv Columns

- `ID` – Row identifier
- `Company` – Customer name (75 unique companies)
- `Quarter` – Time period for sales (Q1–Q9)
- `QuickRatio` – Financial liquidity metric
- `InventoryRatio` – Ratio of inventory to sales
- `RevenueGrowth` – Projected revenue growth
- `MarketshareChange` – Projected market share growth
- `Bond rating` – Company's bond rating
- `Stock rating` – Company’s stock rating
- `Region` – Company's operating region
- `Industry` – Industry category
- `Sales` – **Target variable** (only in train.csv)

### 🔹 EconomicIndicators.csv Columns

- `Month` – Calendar month of the record
- `Consumer Sentiment` – Index based on consumer surveys
- `Interest Rate` – 5-year US Treasury yield
- `PMI` – Purchasing Managers Index
- `Money Supply` – M2 money supply
- `NationalEAI` – National Economic Activity Index
- `EastEAI`, `WestEAI`, `SouthEAI`, `NorthEAI` – Regional Economic Activity Indexes

---

## 📊 Evaluation Metric

- **Mean Absolute Error (MAE)** will be used to score submissions.

---

## 📤 Submission Format

Each prediction must include the following two columns:

ID,Sales 7,110 8,340 16,180 17,500 ...

