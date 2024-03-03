# RFM-Analysis
Sử dụng Python để phân khúc khách hàng.

## I.Introduction
### 1.Business question
- The company SuperStore is a global retail company, hence it has a large customer base. On the occasion of Christmas and New Year, the Marketing department intends to launch marketing campaigns to express gratitude to customers who have supported the company throughout the time. Additionally, the goal is to explore potential customers who may become loyal patrons.

- However, the Marketing department has not yet segmented the customers for this year because the dataset is too large to be manually processed as in previous years. Therefore, they have enlisted the help of the Data Analysis department to assist in implementing a classification algorithm to categorize each customer segment. This will enable the deployment of tailored marketing programs for each customer group.

- Suggestion to the Marketing and Sales teams within the retail model of Superstore would be to focus most on which of the three indices R, F, M?

### 2.Dataset
- RFM Dataset includes 2 tables: e commerce retail and segmentation. E commerce retail table transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

#### 2a. E Commerce Retail Table
![alt](https://i.imgur.com/z59jYOM.png)

#### 2b. Segmentation Table
![alt](https://i.imgur.com/e7qn73E.png)

### 3.Method
RFM stands for Recency, Frequency, and Monetary Value, and it is a method used in marketing and customer relationship management to analyze and categorize customers based on their transaction behavior.

- **Recency (R)**: This measures how recently a customer has made a purchase or engaged with the business. Customers who have made a transaction more recently are often considered more valuable.

- **Frequency (F)**: This measures how often a customer makes a purchase or engages with the business within a specific timeframe. Customers with higher frequency are generally more loyal.

- **Monetary Value (M)**: This measures the total amount of money a customer has spent on purchases. Customers with a higher monetary value are considered high-value customers.

By analyzing and combining these three factors, businesses can create customer segments to target specific groups with tailored marketing campaigns.

## II. Visualization
![alt](https://i.imgur.com/mjMtawB.png)

![alt](https://i.imgur.com/86xON7u.png)

![alt](https://i.imgur.com/8KagbUX.png)

![alt](https://i.imgur.com/VNXFwCu.png)

![alt](https://i.imgur.com/eCraWsX.png)

![alt](https://i.imgur.com/eGC6Rcc.png)

![alt](https://i.imgur.com/ghfGmhW.png)

![alt](https://i.imgur.com/R4cL3nH.png)

![alt](https://i.imgur.com/KrO3I7M.png)

![alt](https://i.imgur.com/mIxffD0.png)

![alt](https://i.imgur.com/TO0qfcp.png)

## III. Insights
### 1. Insights about Recency, Frequency and Monetary of E Commerce Retail
- Through this dataset, SuperStore should prioritize Recency and Frequency over their Monetary value as most of their Champions and Loyal customers make many purchases of low average transactions sizes.
- Average Recency of customers in SuperStore is 113 days. While the median is 71 days, this means there are a lot of high recency values. Although 71 days is not a good number, whenever this number is large, it is likely that customers is going to leave.
- Mean of Frequency is 4 times, this is low for a retail company. Avg time which loyal and champions shoppers purchases is high(12 times), although other customers have very low shopping frequency(1-3 times).
### 2. Insights about customer segments
- Champions and Hibernating customers has the highest numbers with 19.22% and 15.97%. Although hibernating ones just comprise of 3.18% sales.
- While Champions and loyal customers accounts for the most of revenue(~75%).
- There are some negative segment that accounts for a considerable value of customer counts, is At Risk and Lost. They also share a large percentage of sales(9.5%).
- Lastly, some segment make up a small percentage of both count and sales. They are Cannot Lose Them, New Customers, Promising, Need Attention.
### 3. Insights about Champions and At Risk Customers
- Champion Customers spend 553$ for an average purchase, this indicates most of championers purchase mean for 1 time. Most of champions order products which are between 0 -2 dollars. Throughout time, they buy more and more those products, in quarter 4 2011, total products sold have prices between 0-1 dollars is 1.2 millions and 1.1 millions products which their prices are 1-2 dollars. The number of champion customers was also increasing rapidly. In Q4 2010, the number is 143, after 1 year this was 834 customers. The number of invoices show sharp growth, from 477 to 10117 purchases. Although, average cart values increase slightly, from 520 to 553 dollars per invoice. This shows the company have attracted many new champion customers, but the development in selling high-end goods is slow.
### 4. Insights about Potential Loyalist
- Products which are worth 0-2 dollars accounts for the most of products which Potential Loyalist buy.
- The number of customers increase 3 times after 1 year (134 to 411), average cart value increase 30 dollars(180 to 215 dollars).
- However, average repurchase time increases rapidly, from 5 in Q4 2010 to 102 days in Q3 2011, in Q4 2011 people order once in 115 days. This means people order fewer and fewer, we should do something to boost purchasing power.
- The percentage of invoices cancelled decreases through times, as 20% in 2010 Q4 and 14% in Q4 2011.

## IV. Recommendations
| Segment | Characteristics	| Recommendation |
| --- | --- | --- |
| Champions	| Bought recently, buy often and spend the most! | Reward them. Can be early adopters for new products. Will promote your brand. |
| Loyal	| Spend good money with us often. Responsive to promotions.	| Upsell higher value products. Ask for reviews. Engage them. |
| Potential Loyalist | Recent customers, but spent a good amount and bought more than once. |	Offer membership / loyalty program, recommend other products. |
| New customers	| Bought most recently, but not often. | Provide on-boarding support, give them early success, start building relationship. |
| Promising	| Recent shoppers, but haven’t spent much. | Create brand awareness, offer free trials |
| Need attention |	Above average recency, frequency and monetary values. May not have bought very recently though.	| Make limited time offers, Recommend based on past purchases. Reactivate them. |
| About to sleep | Below average recency, frequency and monetary values. Will lose them if not reactivated.	| Share valuable resources, recommend popular products / renewals at discount, reconnect with them. |
| At risk |	Spent big money and purchased often. But long time ago. Need to bring them back! | Send personalized emails to reconnect, offer renewals, provide helpful resources. |
| Cannot lose them | Made biggest purchases, and often. But haven’t returned for a long time. | Win them back via renewals or newer products, don’t lose them to competition, talk to them. |
| Hibernating customers | Last purchase was long back, low spenders and low number of orders. |	Offer other relevant products and special discounts. Recreate brand value. |
| Lost customers |	Lowest recency, frequency and monetary scores. |	Revive interest with reach out campaign, ignore otherwise. |

