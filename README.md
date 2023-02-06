# Online--Retail--Customer--Segmentation


Online-Retail-Customer-Segmentation Customer segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately.

The technique of categorising and grouping consumers according to shared traits is known as customer segmentation. This method also makes it simple to customise and customise your marketing, customer service, and sales initiatives to meet the demands of particular demographics. As a result, client loyalty and conversion rates may increase.

**Problem Statement**

In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

**Data Description**

InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

Description: Product (item) name. Nominal.

Quantity: The quantities of each product (item) per transaction. Numeric.

InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.

UnitPrice: Unit price. Numeric, Product price per unit in sterling.

CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

Country: Country name. Nominal, the name of the country where each customer resides.

**RFM model (Recency, Frequency, Monetary value)**

Recency, frequency, monetary value is a marketing analysis tool used to identify a company's or an organization's best customers by using certain measures.

Recency – How recently did the customer purchase? Frequency – How often do they purchase? Monetary Value – How much do they spend? A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.

Segmentation with K-means clustering: Initially, the data is subject to important stages in an analytics pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton. Then, the unsupervised classification technique, K-means clustering algorithm, is used to determine the ideal segments of customers. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm. The observations from the results are elaborately discussed before reaching the conclusion from the business perspective.

**conclusion**

Missing and duplicate values were found.

Most of the purchases are from the United Kingdom.

Most of the customers have purchased items on Thursday, Wednesday, Tuesday.

Most of the customers have purchased items in November, October, December, and the least number of purchases in April, January, February.

Most of the customers purchase in the afternoon time. The 12th hour of the day is a peak for purchasing items.

we used the K-Means clustering algorithm to find the optimal number of clusters that can separate customers based on their purchasing behavior. We then applied the K-Means algorithm with the Silhouette Score Method on RM, FM, RFM simultaneously. Where we got the optimal number of clusters = 2. We then visualized our results with scatterplots. Then moving forward we applied K-Means with Elbow Method on RM, FM, RFM simultaneously. Next, we applied DBSCAN on RM, FM, and RFM where we got the optimal number of clusters as 2, 2, 3 simultaneously. After that, we applied Dendrogram to find the optimal number of clusters..

So, by applying various algorithms, optimal number of cluster is equal to 2.
