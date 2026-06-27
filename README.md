1.	The dataset contains retail transactions from several countries, with the United Kingdom accounting for the majority of sales.
2.	Missing values, duplicate records, cancelled invoices, and transactions with negative quantities were removed during preprocessing.
3.	The transaction data were transformed into a basket format and one-hot encoded for association rule mining.
4.	The Apriori algorithm identified several frequent itemsets based on the specified minimum support threshold.
5.	Association rules were generated using confidence and lift metrics.
6.	Rules with high lift values (>1) indicate strong associations between products, meaning customers who purchase one product are more likely to purchase the associated product.
7.	These association rules can be used for market basket analysis, product recommendations, cross-selling, and store layout optimization.
