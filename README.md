# epochsTask1
Introduction to Data Science, Recommendation system for online retairing
## Product Recommendation for Online Retailering System
## 1.Dataset Overview
### Dataset: Online Retail dataset for two years
### Shape:541910 rows, 8 columns
### The Online Retailering dataset contains:
#### Invoice number (if c appears==> cancellation) Stock Code, Product Description (name), Quantity, Invoice Date and Time, Per Unit Price, Coustomer ID, Country name.
## 2.Business Problem
### Coustomer loses time in deciding and trying to find the products they prefer.
## 3.Machine Learning Problem
### Type: Recommendation
### Justification
#### The solution is a system that recommends items similar to those a user liked earlier, recommends items based on patterns derived from many users and based on item features provided (price).
## 4.Target Variable & Key Features
### Target Variable:Recommedation
### Key Predictors:Stock Code, Product Description, Quantity, Coustomer id,Unit price, Country name (geography), Invoice Dates.
## 5.Three Key Observations
### 1.Some data sets about item description and coustomer ids were missing.
2.Cancelled transcations are indicate by a Transaction id starting with 'c'.
3.Certain Stock codes are not fully in integer format with alphabets like D for discount, M for manual, S for samples, banking charges and many more.
