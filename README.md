# Pandas Challenge
## Heroes of Pymoli
### This activity utilized Pandas and Python within a Jupyter workbook in order to analyze financial and demographic data.

Congratulations! After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.
Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

The [HeroesOfPymoli ipynb file](../HeroesOfPymoli/HeroesOfPymoli_starter.ipynb) contains the code which outputs the following information:
### Player Count
-Total Number of Players

### Purchasing Analysis (Total)
-Number of Unique Items
-Average Purchase Price
-Total Number of Purchases
-Total Revenue

### Gender Demographics
-Percentage and Count of Male Players
-Percentage and Count of Female Players
-Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)
-Purchase Count
-Average Purchase Price
-Total Purchase Value
-Average Purchase Total per Person by Gender

### Age Demographics
-Bins broken into 4 years (<10, 10-14, 15-19, etc.) of the following:
    -Purchase Count
    -Average Purchase Price
    -Total Purchase Value
    -Average Purchase Total per Person by Age Group

### Top Spenders
-Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
    -SN
    -Purchase Count
    -Average Purchase Price
    -Total Purchase Value

### Most Popular Items
-Identify the 5 most popular items by purchase count, then list (in a table):
    -Item ID
    -Item Name
    -Purchase Count
    -Item Price
    -Total Purchase Value

### Most Profitable Items
-Identify the 5 most profitable items by total purchase value, then list (in a table):
    -Item ID
    -Item Name
    -Purchase Count
    -Item Price
    -Total Purchase Value

# Final Considerations and Observable Trends

Within the gender demographics analysis, it can be seen that on average, females and those who did not disclose their gender payed $0.25 more for their virtual products. The percent of total purchase value for non-males is around 17%, which is slightly higher than their makeup as 15% of the dataset purchases. 

The age distribution of the dataset is slightly skewed left as there are few players under the age of 15, while there are more players at older age ranges. The distribution for average purchase per person does not follow this trend though, as it seems that those closer to the lower and upper bounds (under 19 and over 35) payed more on average compared to those aged 20 to 34, which comprised the middle age range of our dataset. 

Though the biggest spender was *Lisosia93* with 5 purchases for a total of $18.96, the majority of repeat customers,only bought 2 or 3 items. *Lisosia93* was the only user to buy 5 items. 