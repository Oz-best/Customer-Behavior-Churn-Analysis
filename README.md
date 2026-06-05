# Customer-Behavior-Churn-Analysis - Mr. Chuck's Kitchen
Dashboard that uncovers churn patterns. See which customers are at risk and what drives them to leave. Clear visuals for better decisions.                                                                              

# Project Overview
Analyze customer data to identify factors driving churn, understand behavior patterns, and propose strategies to improve retention, engagement, and business growth. The project involves:
1. identifying churn drivers
2. analyzing customer behavior and engagement
3. segmenting customers
4. evaluating impact of discounts, complaints, etc on retention
5. providing data driven recommendations for loyalty and repeat purchases

# Problem Statement
Mr. Chuck's Kitchen is experiencing fluctuations in customers retention, order frequency, and engagement, leading to increasing churn rates and inconsistent repeat purchases, threatening business growth.

# Business Question
This project aims to answer key business questions such as:
1. what characteristics differentiate churned customers from retained customers?
2. does tenure influence the likelihood of churn?
3. how do satisfaction scores relate to customers retention?
4. how do coupon usage and cashback amounts affect repeated orders?
5. what is the relationship between time since last year order and probability?
6. which customer segments (city tier, gender, marital status, etc) show higher churn risk?
7. how dies engagement(hours spent on app, number of devices registered) influence loyalty?
8. what purchasing patterns (order count, preferred order category, order amount growth) predict high value customers?

# Data Collection and Description
The dataset used in this project was given by Truemind Innovation Ltd. for an intership program. Based on the data dictionary, key fields include:
1. customer id - unique customer id
2. churn - churn flag
3. tenure - tenure of customer in organization
4. preferred login device - preferred login device of customer
5. city tier - city tier
6. warehouse to home - distance in between warehouse to home of customer
7. preferred payment mode - preferred payment mode of customer
8. gender - gender of customer
9. hour spend on app - numbers of hours spend on mobile application or website
10. number of device registered - total number of device that is registered on particular customer
11. preferred ordercat - preferred order category of customer in last month
12. satisfaction score - satisfactory score of customer on service
13. marital status - marital status of customer
14. number of address - total number of address on particular customer
15. complain - any complain has been raised in last month
16. order amount hike from last year - percentage increases in order from last month
17. day since last order - day since last order by customer
18. coupon used - total number of coupon that has been used in last month
19. order count - total number of orders that has been placed in last month
20. cashback amount - average cashback in last month

# Tools used 
Python jupyternotebook and PowerBi

# Explore dashboard here
https://app.powerbi.com/groups/me/reports/0cf902b5-ef81-4641-bffa-e27ee4c511bb/ReportSection?experience=power-bi

# Dashboard Insight
The interactive dashboard in PowerBi was designed to present insight clearly and effectively. Key features and insights include:
1. Churn Analysis Page: displays the retained and churned custoemrs, churn complain, churn tenure and churn probability
2. Churn Risk Page: displays different segments with churn risk
3. Customer Analysis Page: shows the loyal, non-loyal, at-risk customers, coupon usage, high and low value customers, and customer satisfaction
4. Key Indicators: total customers 6k(active customer 5k), total orders 15k(avg order 2.65), avg satisfaction score 3.07(satisfied customers 38.75%), churned 16.84%(non-churned 83.16%)

# Key Insights
1. Churn Analysis: The dashboard shows that we have more retained customer than churn by total cashback(₦771k), more churned customers who complained(509), more churned customers who patronized customers only for 1-6 months(666), 20% shows the churn probability of customers ending their patronage between 1-4 days of their last order. This shows that out of our retained customer we have 87 of them were churned, didn't complain and only did busines for 7-12 months. This shows that Mr. Chucks is not really paying attention to his customers' complain and also not providing solutions to their complains.
2. Churn Risk: It shows the percentage risk of Mr. Chucks losing his customers. The dashboard shows the churn risk by segments. Male 17.6% shows more churn rist to Female gender, Single 24.5% shows more churn risk to Divorced and Married staus, City tier3 24.4% show more churn risk to tier 1 and 2, preferred payment method, E-wallet 22.5% shows more churn risk to cash on cash on delivery, credit card, debit card, and unified payment interface. Single customers shows the segment with higher churn risk.
3. Customer Analysis: These analyses the customers' behavior. Rare has a total cashback of ₦803k by coupon usage, neutral has the highes number of satisfaction score 1.6k of retained customers, customers who are at-risk of leaving Mr. Chucks kitchen have more engagement than the loyal and non-loyal customers. it aslo shows that the low value customers mad more repeated orders than our high value customers.
4. These means that Mr. Chucks retained customers are at high risk of churn, low value customers being the main customers of the business can run the business down if solutions are not applied immediately, it also shows that complains from customers are not well handled, thereby making the customers end their business with Mr. Chucks. It also shows that Mr. Chucks don't have efficient and effective loyal customers in his business. It also shows that more repeated orders are not made by the customers, this can be due the online app used to make order and also complains can also come from it. Bad functioning of the online app.

# Recommendations 
1. Improve customer complaint handling by addressing it promptly and effectively to reduce churn risk
2. Focus on high value customers by developing targeted retention strategies for high value customers to increase loyalty and orders
3. Personalized offers by tailoring discounts or services based on customer segments
4. Proactive support by reaching out to at risk customers with support or incentives
5. Targeted engagement for single customers by offering personalized incentives or services to single customers to reduce churn risk
6. Enhance loyalty reward for repeat orders and high value customers
7. Analyse low value customer behavior by understanding why low value customers order more and optimize strategies to increase order value
8. Fix the app issue ASAP
9. Engage at risk customers via other means by reaching out to them via SMS/email with incentives to stay enaged despite app issues.
