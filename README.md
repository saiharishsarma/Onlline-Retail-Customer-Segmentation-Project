# Onlline-Retail-Customer-Segmentation-Project


Problem Statement
In this Project, Our task is to identify major segments on a transnational data set which contains the transactions occuring between 01/12/2010 and 09/12/2011 for a UK based and registered non-store online retail. The company mainly sells unique all- occation gifts. Many customers of the company are wholesalers.

Business Context
Businesses are growing rapidly and serving many customers. So, It is very important to categorize their customers to understand the customer and Business behaviour. It also helps in marketing and Business development.




Data Description:

InvoiceNo: Invoice Number ( Some Invoice No.s are with letter 'C', means cancelled Transaction)(Numeric)

StockCode: Stock Name Code

Description:Description of the product (Numeric)

Quantity: Quantity bought (Numeric)

InvoiceDate: Invoice Date (Date Time)

UnitPrice: Price per Unit (Numeric)

CustomerID: Unique Customer ID (Numeric)

Country: Location



Conclusion:

A. EDA Outcomes:
The retail store has a large share in local region i.e., UK.

The store has least market share in Saudi Arabia.

There are 3877 Unique Descriptions available in Dataset.

Customer ID : 17841 is top most customer by having large count in No. of Purchaces.

Customer with ID 14646 is the buyer of large quantity of the store.

The product having description as "PAPER CRAFT , LITTLE BIRDIE" is the most selling preoduct in store.

B. Challenges:
1. Missing Values - Description &CustomerID are having 0.26% & 24.92% of missing values respectively.

2. Duplicated Data - 5225 in count.

3. Outliers - Quantity & Unit Price Columns.

C. Modelling Summary:
1. We can observe that the TWO clusters are clearly formed using KMeans- Elbow Approach.

2. We can observe that the TWO clusters are clearly defined using KMeans- Silhouette Analysis Approach.

3. The TWO clusters are clearly seperated using Hierarcheal clustering using Dendrogram Approach.

4. The clusters are clearly seperated using DB SCAN clustering. DB Scan also creates few noise data points on clustering, which can exempted. Hence, the no. of optimal clusters can be 2.

5. Model1 i.e, KMeans with Elbow Approach having highest Score, Hence, we can conclude that it works better for clustering on this data.

6. Finally, We formed TWO Clusters:

Cluster 1 - Low Recency, High Frequency and High Monetory Values

Cluster 2 - High Recency, Low Frequency and Low Monetory Values


-----------------------------------------------------------------------------------
For any suggestions/ doubts, kindly contact through mail.

mail id:
saiharish.swarna@gmail.com

===== Thanks for Reading ===
