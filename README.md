![image](https://github.com/vbs30/Basket-Trends-Understanding-Consumer-s-Choice/assets/95699405/74d4bdc6-fcaa-4271-baf2-295bd57e78ce)# Basket-Trends-Understanding-Consumer's-Choice

Basket Trends: Understanding Consumer's Choice is a valuable data mining technique used in retail to explore customer purchase behavior and uncover relationships 
between products frequently bought together. This proposed work uses Market Basket Analysis to understand what products customers tend to buy together when shopping. 
By analyzing this data, retailers can improve their marketing strategies, arrange products on shelves more effectively and increase sales by offering complementary 
products to customers. The goal is to gain insights that help businesses make smarter decisions to enhance the shopping experience and increase customer satisfaction.

Working of the Project: 

![image](https://github.com/vbs30/Basket-Trends-Understanding-Consumer-s-Choice/assets/95699405/02a5892e-447c-4332-ba4d-0861cf92a5a4)

Block Diagram

This Project involves analyzing customer buying habits to identify associations between different items placed in their baskets. The insights obtained can be used by 
retail companies to develop marketing strategies and optimize sales.

Our system begins by importing the necessary libraries and packages required to perform the algorithm. This is followed by data cleaning and pre-processing, where the 
data is read and necessary changes are made to prevent errors during the application of various algorithms. Our system utilizes the Online Retail Dataset from the years 
2010-2011 and identifies relevant columns and values for the algorithm. The Apriori Algorithm, which is a part of the Association Rule, is used for the analysis.

Next, our system creates frequent itemsets that will be used to derive association rules. These frequent itemsets serve as the basis for defining the association rules. 
The association rule is then executed with the help of the frequent itemset, and our system displays all the rules that are formed based on the given conditions. 
It provides the rules, their support, confidence, and lift for every displayed rule. This step is followed by data visualization, where our system uses the rules and 
their measures to create different graphs that provide pictorial information about the results obtained.

Our system also provides recommendations for a particular product. For instance, when X is bought, we can sort the probability of buying Y (confidence) and make a 
product offer, or we can make an offer based on how many times the probability of sales over the lift increases. We can also make a product recommendation with a 
hybrid filtering approach that utilizes support, lift, and confidence together. Therefore, our system not only provides rules based on frequent itemsets but also 
offers actual recommendations, which is particularly useful for e-commerce.

