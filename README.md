# Credit-Card-Case-Study
Market Segmentation_SQL and Tableau



## The Business:
Sparrow Is a fintech company offering Sparrow Credit Card launched in October 2023 <br>
Providing credit to the sub-prime segment including those with limited or no credit history.

## Sparrow’s Key differentiators: 
Sparrow promises to guide its customers to financial freedom by empowering them through rewards for responsible credit usage. Sparrow offers 1% cashback simply for making on-time monthly payments, which is different from the usual cashback rewards for spending. Sparrow reports on-time payments to the three major credit bureaus, ensuring customers receive the credit they deserve for managing their accounts well. Responsible account management is rewarded with increased credit limits.<br>

Another of Sparrow’s unique selling points is its cutting-edge mobile app. Upon approval, Sparrow provides an instant virtual card with a $300 limit while customers wait for their physical card, offering more convenience than most traditional banks. The app allows customers to track spending, make payments, freeze cards, and manage their accounts with speed and flexibility.

## The Task: 
Study Sparrow's existing customer data to Improve customer retention and lifetime value, enhance customer engagement and spending. Find and target the group of top customers with high spend and value then work to tailor sales and promotions to these group of customers to ensure retention. 

## Extract dataset using MySQL for Tableau using 
**suggested Metrics :** <br>
Existing customers with Utilization Ratio ≤ 30%  , Lifetime Usage of at Least 12 Months ,  exclude unknown income information 

**Exploring the dataset then extract .csv for Tableau** <br>
1. Check that there are no duplicates in our primary key : CLIENTNUM <br>
insert pic1

2. Check for NULL VALUES in required columns <br>
repeat this step for all required columns : Attrition_Flag, Credit_Limit, Total_Revolving-Bal, Avg_Open_To_Buy, Avg_Utilization_Ratio <br>
insert pic2

3. After checking that the required information is all in, we extract the data to Tableau <br>
insert pic3

## Visualize the data in Tableau
link to Tableau project

Tableau has made 4 distinct clusters from the dataset 
Rename the 4 clusters respectively to: 
Buy More | Spend More (red)
Buy More | Spend Less (orange)
Don’t Buy | Don’t Spend (green)
Low Buy | Low Spend (blue)
insert pic4

## Gather Insights from Best segment 
We will be looking into these demographics of the best cluster to gather insights 

insert pic5


