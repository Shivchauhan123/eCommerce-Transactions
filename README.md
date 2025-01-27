# eCommerce Transactions Data Analysis

This repository contains the solution for the eCommerce data , which includes tasks like Exploratory Data Analysis (EDA), Lookalike Model creation, and Customer Segmentation.

## Table of Contents

1. [Overview](#overview)
2. [Task 1: Exploratory Data Analysis (EDA)](#task-1-exploratory-data-analysis-eda)
3. [Task 2: Lookalike Model](#task-2-lookalike-model)
4. [Task 3: Customer Segmentation / Clustering](#task-3-customer-segmentation-clustering)
5. [Installation Instructions](#installation-instructions)
6. [File Naming Convention](#file-naming-convention)
7. [References](#references)

## Overview

The dataset provided consists of customer, product, and transaction information. The goal of this assignment is to analyze the data to derive actionable insights and build predictive models. The dataset includes the following files:

- **Customers.csv**: Information about customers (CustomerID, Name, Region, SignupDate).
- **Products.csv**: Information about products (ProductID, ProductName, Category, Price).
- **Transactions.csv**: Information about transactions (TransactionID, CustomerID, ProductID, TransactionDate, Quantity, TotalValue, Price).

## Task 1: Exploratory Data Analysis (EDA)

The EDA task involves the following:
- Loading and cleaning the provided data.
- Conducting exploratory analysis to understand customer behavior, product popularity, and transaction patterns.
- Deriving actionable business insights from the data.

**Output**: The results are provided in the form of a PDF report and the corresponding Python notebook.


- **File**: `FirstName_LastName_EDA.ipynb` (Jupyter Notebook with EDA code)

## Task 2: Lookalike Model

For the Lookalike Model, the goal was to recommend similar customers based on their transaction history and profile. This task involved:
- Merging customer and product data.
- Calculating similarity scores between customers based on their profile and transaction behavior.

**Output**: The top 3 similar customers for each customer (CustomerID: C0001 - C0020) with their similarity scores.

- **File**: `FirstName_LastName_Lookalike.csv` (Contains Lookalike Recommendations)
- **File**: `FirstName_LastName_Lookalike.ipynb` (Jupyter Notebook with Model Code)

## Task 3: Customer Segmentation / Clustering

The goal of this task was to segment customers based on their profile and transaction history:
- Applied a clustering algorithm (e.g., K-Means) to form customer groups.
- Evaluated the clustering performance using metrics such as the **DB Index**.
- Visualized the clusters.

**Output**: A report detailing the segmentation results, including cluster characteristics and clustering metrics.

- **File**: `FirstName_LastName_Clustering.ipynb` (Jupyter Notebook with Clustering Code)
