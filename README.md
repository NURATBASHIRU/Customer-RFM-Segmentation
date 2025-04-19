# Customer-RFM-Segmentation

# Introduction

RFM Customer Segmentation is a marketing analysis technique used to identify and classify customers based on their purchase behavior. The term RFM stands for;
Recency (R) - how recently a customer made a purchase.
Frequency (F) - how often a customer makes a purchase.
Monetary (M) - How much money a customer spends on purchases.

The result of this analysis is projected in a highly responsive dashboard created on Power BI. See Picture below;
<img width="634" alt="Dashboard" src="https://github.com/user-attachments/assets/9660963c-f826-48a0-85e8-003808191b5b" />

# Problem statement 
An ecommerce store wants to put up a marketing campaign and it has become really important for them to access their customers based on RFM segmentation in order to determine which customers are more likely to interact with it marketing campaign. And to project it’s campaign turnover rate.

# Steps taken / data transformation process 
## Data Cleaning and Transformation Process
### 1. Recency Column
The recency column contains the difference in number of days between the reference date (the most recent date in the dataset - 31/12/2017) and the last purchase date of each customer.

### 2. Frequency Column 
The frequency column contains the number of time each customer shops with the store. Using Customer ID as a unique Identifier.
<img width="960" alt="Frequency Score" src="https://github.com/user-attachments/assets/a7d52db2-cd2f-4ba2-9468-2a7fa24aa282" />

### 3. Monetary Column
The monetary column contains the total value of all the items purchased by each customer.

### 4. Recency Score
I created a recency score of 1 - 5. 5 being the most recent purchase date and 1 being the least recent purchase date.

### 5. Monetary Score
I created a monetary score of 1 - 5. With 5 being the highest spender and 1 being the least.

### 6. RFM Pattern
I assigned different Segment names to classify customers based on shared characteristics - RFM score
<img width="960" alt="RFM Pattern" src="https://github.com/user-attachments/assets/20b452b4-0295-403c-bf34-ef67c04236c5" />




Insights and Recommendations 
1. “At risk” - customers whose RFM score start with 1 - customers constitute a larger share of the RFM Segment and consequently sum up a large share of sales as well
