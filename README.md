Introduction

Olist dataset is a collection of information about all transaction data of an e-commerce platform in Brazil in period from 2016 to 2018 and includes various details about the orders, such as their status, price, payment and shipping performance. It also provides insights into customer location, product attributes, and customer reviews. This dataset can be useful for analyzing and understanding various aspects of e-commerce operations in Brazil. we using this data for final test of Pacmann academy. 


Data Scheme

![image](https://github.com/fadilc/data-wrangling/assets/118906826/7713611e-d12f-42a0-8850-9947f6f7623e)


Objectives Question for thid project:

Exploratory Data Analysis (EDA)

Best month of sales and how much the profit?

Top 10 product sales from Olist e-commerce?

Most payment type that customer use by the AOV value?

Top 10 city with high product sales?

What time we should display the product?

Recency, Frequency, Monetary (RFM) Analysis
guide for (RFM) : https://documentation.bloomreach.com/engagement/docs/rfm-segmentation

The problem is that doing this meant creating 125 (5x5x5) customer segments, which does not allow us to obtain useful information that can be converted into real action. For example, it is unfeasible to run 125 personalized marketing campaigns.

To solve this problem, you can create groups with the 125 segments we obtained earlier. In order to create them, it is important to keep the following in mind: The new segments must be large enough to be "actionable" (usable) but small enough to be identified as a distinct group. A group made up of consumers with very different buying behaviors is useless.

For this project, I will use the bloomreach segmentation model (link to blog), which contains the following 11 customer segments.

![image](https://github.com/fadilc/data-wrangling/assets/118906826/815364bc-c1ac-4358-8514-13d8a1b13a8d)


Note: it is important that the scores have been concatenated in order to match the values in the table. That is, the recency should be first, then the frequency and finally the monetary (RecencyFrequencyMonetary score).

source : https://www.kaggle.com/code/marta99/olist-e-commerce-eda-and-rfm-analysis#RFM-ANALYSIS



