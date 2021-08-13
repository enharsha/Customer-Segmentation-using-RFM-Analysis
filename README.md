# Customer-Segmentation-using-RFM-Analysis
It is a critical requirement for business to understand the value derived from a customer. RFM is a method used for analyzing customer value. Customer segmentation is the practice of segregating the customer base into groups of individuals based on some common characteristics such as age, gender, interests, and spending habits Perform customer segmentation using RFM analysis. The resulting segments can be ordered from most valuable (highest recency, frequency, and value) to least valuable (lowest recency, frequency, and value).

Dataset Description

This is a transnational data set which contains all the transactions that occurred between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique and all-occasion gifts.

    InvoiceNo - Invoice number. Nominal, a six digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation
    StockCode - Product (item) code. Nominal, a five digit integral number uniquely assigned to each distinct product
    Description - Product (item) name. Nominal
    Quantity - The quantities of each product (item) per transaction. Numeric
    InvoiceDate - Invoice Date and time. Numeric, the day and time when each transaction was generated
    UnitPrice - Unit price. Numeric, product price per unit in sterling
    CustomerID - Customer number. Nominal, a six digit integral number uniquely assigned to each customer
    Country - Country name. Nominal, the name of the country where each customer resides
    
In this project I performed Data Wrangling and Cohort Analysis on transaction data of Online Retail Store. Calculated RFM metrics and performed cluster analysis using K-means, to obtain 4 segments in customer base. Created a dashboard in Tableau to summarize results.

