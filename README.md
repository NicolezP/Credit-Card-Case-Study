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
**Suggested Metrics :** <br>
Existing customers with Utilization Ratio ≤ 30%  , Lifetime Usage of at Least 12 Months ,  exclude unknown income information 

**Exploring the dataset then extract .csv for Tableau** <br>
1. Check that there are no duplicates in our primary key : CLIENTNUM <br>
![](ReadMe%20Images/1.PNG)<br>

2. Check for NULL VALUES in required columns <br>
repeat this step for all required columns : Attrition_Flag, Credit_Limit, Total_Revolving-Bal, Avg_Open_To_Buy, Avg_Utilization_Ratio <br>
![](ReadMe%20Images/2.PNG)<br>

3. After checking that the required information is all in, we extract the data to Tableau <br>
![](ReadMe%20Images/3.PNG)<br>
<br><br>
## Visualize the data in Tableau
**Tableau has made 4 distinct clusters from the dataset** 
<br><br>
These 4 clusters are:<br> 
Buy More | Spend More (red)<br> 
Buy More | Spend Less (orange)<br> 
Don’t Buy | Don’t Spend (green)<br> 
Low Buy | Low Spend (blue)<br> 
<br>
![](ReadMe%20Images/4.PNG)
<br><br>
## Gather Insights from Best segment 

Analyse the demographics of the best cluster to gather insights 
<br><br>
**[link to vizzie in Tableau Public](https://public.tableau.com/views/CreditCard_MarketSeg/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**
<br><br>
![](ReadMe%20Images/Dashboard%201.png)<br>
<br>
### Demographic of "Buy More | Spend More" clients
*    Majority are in the age range of 40 to 53 years old  of Male Gender 73%
*    Majority earning an Annual income of $60-120k+ with 2-3 dependents
*    Mostly Married   Graduate and College Education 
* 	 Average Month on Book is 36 Months , 3 years
### Suggestions 
The dataset is great for a segmentation study. We can recommend tailoring promotions to fit their lifestyles, such as offering cashback rebates for groceries and petrol. Additionally, we could suggest a sign-up bonus of $500 after spending $5,200 over three months, attracting customers who are confident they can meet this spending requirement. The average tenure is 36 months, and one reason for potential churn could be the high annual fee of $99 after the first year. Sparrow Card might consider offering renewal rebates to customers in this segment after 36 months to encourage loyalty.
### Additional data we could investigate
To design an effective marketing programme to further engage customers in this segment, we would have to dive into their spending data. It would also help to find out the net promoter index by surveying the customers in this segment on how likely they are to recommend this card to their peers and any feedback they might offer to improve the engagement and services to offer.



