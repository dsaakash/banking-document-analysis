# Banking Document Data Processing and Analysis

## Introduction

This project involves processing and analyzing simulated banking document data extracted with OCR. The dataset includes various complexities such as OCR-like errors, transactions with currency symbols, multiple transaction types, and aggregated data. The objective is to develop a Python script to perform data cleaning, analysis, and anomaly detection tasks.



## Dataset

The dataset is provided in a CSV file named banking_data_assignment.csv. It contains the following columns:



- **Transaction Date**
- **Account Number**
- **Transaction Type**
- **Amount**
- **Description**

## Task Overview

1. Data Cleaning
   - Correct OCR-like errors in account numbers and    descriptions.
- Normalize amount values to a consistent format, handling currency symbols and negative values for withdrawals.
2. Data Analysis
  - Identify and separate individual transactions from aggregated data (subtotals/yearly totals).

- Reconcile transactions by ensuring the consistency of aggregated data with individual transactions.
Anomaly Detection
- Detect and flag any unusual transactions that could indicate errors or fraudulent activity based on criteria such as unusually high transaction amounts.
- Reporting
   - Generate a report summarizing the findings from the analysis, including any discrepancies in reconciliation and a list of detected anomalies.

