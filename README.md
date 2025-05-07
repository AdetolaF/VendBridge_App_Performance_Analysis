# VendBridge_App_Performance_Analysis
## Business Problem
VendBridge App, launched by NexaLink as a digital marketplace platform, has undergone significant marketing initiatives aimed at establishing a strong market presence and increase in user adoption. It's 3 months post launch and NexaLink wants to understand the App Engagement, Performance and User Adoption.
## Business Objective
- To understand and monitor user adoption and engagement of VendBridge app since inception
- To understand region leaderboard based on user activity and engagement
- To forecast user activity for the next 30, 60 and 90 days based on historical trends.
## Data Preparation and Transformation
The raw dataset included daily records across multiple metrics which include installations, uninstalls, sign-ups, app crashes, daily active users, transaction counts, average time spent, date and region. Several calculated fields were created to support user insights. These includde: Sign-up Rate = User Sign-ups/Total app installs; Churn Rate = Uninstalls/User sign-up; Engagement Score = Weighted combination of Daily Active User, transaction counts and avg. time spent per user. Aggregations such as average, sum, etc. were applied to derive daily and regional performance metrics.
## Dashboard Development
The dashboard was developed in Tableau. Four dashboards were developed to showcase User Acquisition Report, Engagement, Region Leaderboard performance and User Activity Forecast. Interactive elements such as filters, parameter controls and dynamic KPIs were embedded to enhance user exploration. Tableau's built-in exponential smoothing model was used to project 30, 60 and 90 days forecast for the key metrics.
## Result
Dashboard Link: (https://public.tableau.com/app/profile/adetola1161/viz/VendBridgeAppPerformanceAnalysis/Leaderboard)
- User Acquisition Report
The data revealed consistent growth in both app installations and user sign-ups with slightly varying rates. From June to July, app installations grew by 8.86%, followed by 9.01% increase in August. User sign-ups also increased with 6.79% from June to July but decreased to 5.33% from July to August. Overall, there was a consistent growth in user adoption of the app over time with increasing app installations and reduction in churn rate. However, decrease in sign up rate may be due to regular app crashes as seen in the data.
![image](https://github.com/user-attachments/assets/9a213829-dfc5-401c-b7d7-98f359692f8e)
- Engagement Report
The engagement report showed decrease in transaction count from June to July with a percentage of  - 14.22% which later increased from July to August with a percentage of 10.95%. Average time spent per user also increased from 85 mins to 107 mins and daily active users also increased from 2800 to 3071 in August. However, the data showed that less than 1% of the total people that sign up on the app are daily active users.
![image](https://github.com/user-attachments/assets/7546ab9f-69d5-455c-a71d-aafb86cbcc7f)

- Regional Leaderboard Performance
The regional leaderboard performance revealed that majority of our users are from the US and the engagement score and transaction count is also highest in this region. This was followed by EMEA, Canada, APAC and LATAM respectively.
![image](https://github.com/user-attachments/assets/ae26b729-4f6f-4ace-ac2f-be4698d2b6ed)
- User Activity Forecast
The 30 to 90 days forecast showed that there will be increase in Daily Active Users and Total app installations over time , hoever, with occasional dips. It also revealed that there will be steady decline in total app uninstall while transaction counts remain on average.
![image](https://github.com/user-attachments/assets/bc692abd-7a86-48a8-8f9a-987f8982539f)
## Recommendation
- App stability need to be improved to encourage user adoption
- There should be follow up on user review to understand customer perspectives
- More marketing campaign need to be done in all region and most especially in the region with lower usage.
- The company can introduce incentives or points that can promote user adoption and retention.

 

