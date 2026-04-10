# Ecommerce-Customer-Behavior ( Python )
## Project Objective 
To analyze customer type, total spend, items purchased and customer loyalty.

## Dataset Used
- <a href="https://github.com/myolwinhein-data/Ecommerce-Customer-Behavior-Python-/blob/main/E-commerce%20Customer%20Behavior.csv">Customer Behavior Dataset</a>

## Questions ( KPIs )
- The age-group who is our biggest customer.
- Which city has the highest spending customer?
- Which member type customer spend the most?
- Comparing gender ( male or female ).
- The relationship between item purchased and total spend.
- Which member type is the best loyalty?

## Process
- Import the libries ( pandas,numpy,matplotlib,seaborn)
- Loading the data file & checking the data & apply data cleaning
- Applying exploratory data analysis and generated business insights.

## Code File
- <a href="https://github.com/myolwinhein-data/Ecommerce-Customer-Behavior-Python-/blob/main/Ecommerce%20Customer%20Behavior.ipynb">Ecommerce Customer Behavior Analysis</a>

## Business Insights
- Gender distribution is balanced around 50% for each gender(male&female). However Male Customer has a higher average total spend compared to Female Customers.Therefore we should focus on Male Customers. We should sold Male Customer products more than Female's products.
- The majority of our customers are between 28 and 32 years old.In terms of total spend,the 28 has the highest spend,followed by the 30, 29, 31 as the highest spenders.We need to keep the 28-32 age group_customers. Give some favor not to lose top customers.For example:give promotion on the favorite products of that age_group.
- In total spend, Gold Members are the top spenders and Silver Member are second and Bronze Members are the third. This show the higher the Membership Tier, the higher the total spend.
- In Membership Loyalty, Gold Members have the lowest number of days ,the shortest purchase interval.Gold Members provide the top in total spend and purchase frequency.Therefore give the special promotions to upgrade the Membership Types , from Bronze Members to Silver and Silver to Gold.
- The correlation between items purchased and total spend is a strong relationship (+0.97). Therefore increasing the number of items purchased is the key to get higher total sales.The relation between Items Purchased and Discount Applied is a negative relationship (-0.11). In Bar Chart, without a discount is a slightly higher average number of purchased compared to discount purchased.Giving discount is not effective on items purchased. Therefore we should shift to Quantity-based Promotions like 'Buy 2 Get 1 Free'.
