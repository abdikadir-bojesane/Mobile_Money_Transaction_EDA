# Mobile Money Transaction EDA

## Overview

This project explores a mobile money transaction dataset using Microsoft Excel. The workbook brings together transaction records, validation checks, descriptive summaries, and PivotTable analysis to examine transaction activity, customer segments, transaction values, locations, and transaction types.

## Dataset

The dataset contains **14,997 transaction records** covering **1 January 2025 to 31 December 2025** across **11 cities** and **4,340 customers**.

The transaction fields are:

* TransactionID
* TransactionDate
* TransactionTime
* TransactionType
* CustomerID
* CustomerName
* CustomerSegment
* Amount_USD
* CompletionTime_Seconds
* AgentID
* MerchantCategory
* City
* Region
* DeviceType
* Status
* Flagged Amount

## Project Objectives

* Organize and review the transaction data.
* Validate important fields and summarize basic data checks.
* Understand the structure and distribution of the dataset.
* Explore transaction amounts, customer segments, monthly activity, cities, and transaction types.
* Compare transaction counts, total amounts, shares, and average transaction values.
* Present key results using Excel formulas, summary tables, and PivotTables.

## Workbook Contents

The workbook is organized into four worksheets:

| Worksheet | Description |
|---|---|
| `Transactions` | Transaction level dataset containing 14,997 records and 16 fields. |
| `Validation` | Basic validation outputs, including the row count, number of cities, and total transaction amount. |
| `EDA SUMMARY` | Descriptive statistics and summary analysis covering customer segments, monthly activity, cities, and transaction types. |
| `Pivot` | PivotTable analysis of customer segments, including transaction counts and shares, total amounts and shares, and average transaction values. |

## Key Findings

* **14,997 transactions** from **4,340 customers** across **11 cities**.
* The recorded period runs from **1 January 2025 to 31 December 2025**.
* Total transaction value is approximately **$1,209,856.02**.
* Average transaction value is approximately **$80.67**, while the median is **$20.03**.
* Individual customers account for approximately **73.7% of all transactions**.
* Diaspora customers have the highest average transaction value, approximately **$333.97**.
* Mogadishu records the largest transaction count, with **6,314 transactions**, approximately **39.5%** of all records.
* Send Money is the most frequent transaction type, with **4,530 transactions**.

## Tools and Techniques

* Microsoft Excel
* Excel formulas
* Data validation
* Descriptive statistics
* PivotTables
* Exploratory Data Analysis (EDA)

## Repository Structure

The repository contains the project documentation and the original Excel workbook:

* `README.md`
* `mobile_money_transactions.xlsx`

## Further Analysis

Possible extensions include a deeper review of transaction status and completion times, customer and agent activity, device usage, flagged transactions, unusual values, and an interactive dashboard.

## Author

**Abdulkadir Ahmed**
