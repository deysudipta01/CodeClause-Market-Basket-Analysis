# CodeClause-Market-Basket-Analysis
Market basket analysis is a data mining technique retailers use to increase sales by better understanding customer purchasing patterns. It involves analyzing large data sets, such as purchase history, to reveal product groupings and products likely to be purchased together. 
## Objectives
To understand what Market Basket Analysis is and how it is used.
To learn about the various algorithms used in Market Basket Analysis.
To learn to implement the algorithm in Python.
## Market Basket Analysis
Market basket analysis is a strategic data mining technique used by retailers to enhance sales by gaining a deeper understanding of customer purchasing patterns. This method entails the examination of substantial datasets, such as historical purchase records, in order to unveil inherent product groupings and identify items that tend to be bought together. 

By recognizing these patterns of co-occurrence, retailers can make informed decisions to optimize inventory management, devise effective marketing strategies, employ cross-selling tactics, and even refine store layout for improved customer engagement.

For example, if customers are buying milk, how probably are they to also buy bread (and which kind of bread) on the same trip to the supermarket? This information may lead to an increase in sales by helping retailers to do selective marketing based on predictions, cross-selling, and planning their ledge space for optimal product placement.
Now, just think of the universe as the set of items available at the store, then each item has a Boolean variable that represents the presence or absence of that item. Now each basket can then be represented by a Boolean vector of values that are assigned to these variables. The Boolean vectors can be analyzed for purchase patterns that reflect items that are frequently associated or bought together. Such patterns will be represented in the form of association rules.

## How Does Market Basket Analysis Work
Collect data on customer transactions, such as the items purchased in each transaction, the time and date of the transaction, and any other relevant information.
Clean and preprocess the data, removing any irrelevant information, handling missing values, and converting the data into a suitable format for analysis.
Use association rules mining algorithms such as Apriori or FP-Growth to identify frequent item sets, sets of items often appearing together in a transaction.
Calculate the support and confidence for each frequent itemset, which expresses the likelihood of one item being purchased given the purchase of another item.
Generate association rules based on the frequent itemsets and their corresponding support and confidence values. Association rules express the likelihood of one item being purchased given the purchase of another item.
Interpret the results of the market basket analysis, identifying which items are frequently purchased together, the strength of the association between items, and any other relevant insights into customer behavior and preferences.
Use the insights from the market basket analysis to inform business decisions such as product recommendations, store layout optimization, and targeted marketing campaigns.

 
## Types of Market Basket Analysis 
### Predictive Market Basket Analysis
employs supervised learning to forecast future customer behavior. By recognizing cross-selling opportunities through purchase patterns, it enables applications like tailored product recommendations, personalized promotions, and effective demand forecasting. Additionally, it proves valuable in fraud detection.
### Differential Market Basket Analysis
compares purchase histories across diverse segments, unveiling trends and pinpointing buying habits unique to specific customer groups. Its applications extend to competitor analysis, identification of seasonal trends, customer segmentation, and insights into regional market dynamics.

## Algorithms Used in Market Basket Analysis
### Apriori Algorithm
Apriori Algorithm is a widely-used and well-known Association Rule algorithm and is a popular algorithm used in market basket analysis. It is also considered accurate and overtop AIS and SETM algorithms. It helps to find frequent itemsets in transactions and identifies association rules between these items. The limitation of the Apriori Algorithm is frequent itemset generation. It needs to scan the database many times, leading to increased time and reduced performance as a computationally costly step because of a large dataset. It uses the concepts of Confidence and Support.

## Implementing Market Basket Analysis in Python

### Here are the steps involved in using the apriori algorithm to implement MBA:

First, define the minimum support and confidence for the association rule.

Find out all the subsets in the transactions with higher support(sup) than the minimum support.

Find all the rules for these subsets with higher confidence than minimum confidence.

Sort these association rules in decreasing order.

Analyze the rules along with their confidence and support.
