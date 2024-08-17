# Maven-Pizza-challenge
![images (7)](https://user-images.githubusercontent.com/108612390/193467417-26c85e60-7998-4b89-8015-120f30f6f86e.png)

# Introduction
The Maven Plato pizza dataset contains 4 csv files representing a year's worth of sales from a fictitious pizza place, including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, and ingredients.
# Recommended Analysis
- what days and times do we tend to be busiest?
- How many pizzas are we making during peak periods?
- what are our best and worst selling pizzas?
- what is our average order value?


# Tools used for analysis
- Microsoft Excel: I utilized Ms Excel to view the datasets and properly understand the parameters of the data. I also performed some cleaning to make the dataset alot easier to work with/analyse
- PostgreSQL: This is a great tool for retrieving data of which i used in performing detailed analysis with the aid of the operators, general SQL syntax to retrieve the necessary data
- Power BI: The microsoft Business intelligence tool was very helpful in my visualization process. I imported the datasets into Power BI and created a singular dashboard that is clear and visually appealing

- Dashboard using Power BI
- 
![Screenshot (66)](https://user-images.githubusercontent.com/108612390/194346831-d5fa70e2-9bae-47d7-84ef-10d770964ad6.png)

- click on the link below to interact with the dashboard
https://app.powerbi.com/view?r=eyJrIjoiOGE5YWJiMWEtM2M5MS00M2YwLWJjZDUtOWNiODcyNTU0ZTBhIiwidCI6IjI3MTZhMTNmLTBhOTMtNGZlMy1hYTMxLTQ4ZDgxNTA1ZTdlNiJ9

- Futher Analysis was performed using PostgreSQL
https://github.com/rosemarychiwuzie/Maven-Pizza-challenge/blob/main/PostgreSQL%20Analysis%20on%20Maven%20Pizza%20Challenge.txt

# The Analysis
![Screenshot (60)](https://user-images.githubusercontent.com/108612390/194349332-97fe168d-d622-4bba-a79b-f7d2af9541fe.png)
- The busiest hours appears to be 12pm to 2pm(mid-day)

![Screenshot (61)](https://user-images.githubusercontent.com/108612390/194350181-4701afb0-3551-4df5-bf21-f823b7e05dc8.png)
- The best selling pizza is the The Thai Chicken Pizza while the least selling Pizza is The Brie Carre Pizza

![Screenshot (62)](https://user-images.githubusercontent.com/108612390/194350891-d8cc65a7-f30c-47d5-87a9-de4511b044e3.png)
- Plato Pizza place recorded the most sales 2015 on Sundays followed by Mondays and the least number of order and sales is on Thursdays

![Screenshot (63)](https://user-images.githubusercontent.com/108612390/194351514-c24aa062-0a4f-4d44-b62d-0974787e026a.png)
- Customers appreciate and purchase the Large sized Pizza more than the other available sizes. The Size XXL on the other hand is the least purchased

![Screenshot (64)](https://user-images.githubusercontent.com/108612390/194352347-affe1bc2-c09e-4b51-9527-c0d433239ba6.png)
- The month July recorded the most number of orders and sales and a decline of sales in October as it recorded the least number of orders. Plato pizza surely needs to work on sales during autumn.

![Screenshot (65)](https://user-images.githubusercontent.com/108612390/194353332-d60c0ae1-dbe9-4f06-a061-f57764b1e954.png)
- The visual above shows the intensity of sales by size and category of pizzas. Apparently there are just four categories of pizzas at plato's place and the Large sized in Category Veggie seems to be the customers favourite while size XXL in category Classic is the customers least favourite

# Insights
- Average Pizza price is $16.4
- The Thai Chicken Pizza generated the most revenue totalling $43,434 while the Brie Carre Pizza generated the least sales of $11,588
- Size L(large) appears to have the most quantity of orders of 18,956 while size XXL(extra extra large) has the least of 28 orders
- July recorded the most number of sales with $72,557 followed by may, march, november... Going forward plato pizza would require more hands to handle mid_year orders 
- Plato Pizza makes the most sales on sundays which is understandable as family and friends gather during the weekend and refreshments like pizza would be a must
- The peak hour generating the most sales appears to be mid-day of 12pm-2pm
- On peak periods typically sundays, plato pizza gets over 8,000 orders.
