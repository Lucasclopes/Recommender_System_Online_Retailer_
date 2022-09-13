# Recommender_System
Build a recommender system that is able to facilitate user choices by recommending items the user likes and improve user experience when making gifts purchases on the website

**Summary:** Initially, a market basket analysis was required, in order to identify key customer behaviours and dive deeper into the business. Then, a recommender was developed in order to suugest new products the clients might be interestd in. 

**Keywords**: Python, Predictive Model, Machine Learning, Neural Networks, Decision Trees, Random Forest, Gradient Boost

## Important libraries and packages 
- pandas, numpy
- seaborn, matplotlib
- mlxtend (apriori, association_rules)
- lightfm (https://github.com/lyst/lightfm)

## Data
- InvoiceNo	- Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- StockCode	- Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description	- Product (item) name. Nominal.
- Quantity	- The quantities of each product (item) per transaction. Numeric.
- InvoiceDate	- Invoice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice -	Unit price. Numeric, Product price per unit in pounds.
- CustomerID -	Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country	- Country name. Nominal, the name of the country where each customer resides.

**Note:** The data concerns transactions occurring between 01/12/2010 and 09/12/2011. Over that particular period, there were 25900 valid transactions in total, associated with 4070 unique items and 4372 customers from 38 different countries. The dataset has 541909 instances.

## Steps
- ### Importing and understanding	the data 
- ### Analysis of Duplicates, Missing Values and Data Types	
- ### Data Preparation	
- ### Coherence Checking	and Outlier detection
- ### Market Basket Analysis	(construct association rules and identify items frequently purchased together)
- ### Recommendation System (lightfm - https://github.com/lyst/lightfm)
