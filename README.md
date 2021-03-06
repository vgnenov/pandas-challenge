# Pandas, Pandas, Pandas

![Screenshot](Instructions/Screenshots/Fantasy.jpg "Screenshot")

## Purpose
Analyze the data for a recent fantasy game Heroes of Pymoli.  The game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience.  The company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

Final report should include each of the following:

### Player Count
- Total Number of Players

### Purchasing Analysis (Total)
- Number of Unique Items
- Average Purchase Price
- Total Number of Purchases
- Total Revenue

### Gender Demographics
- Percentage and Count of Male Players
- Percentage and Count of Female Players
- Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)
- The below each broken by gender:
    - Purchase Count
    - Average Purchase Price
    - Total Purchase Value
    - Average Purchase Total per Person by Gender

### Age Demographics

The below each broken into bins of 4 years (i.e. <10, 10-14, 15-19, etc.)

- Purchase Count
- Average Purchase Price
- Total Purchase Value
- Average Purchase Total per Person by Age Group


### Top Spenders

-  Identify the the top 5 spenders in the game by total purchase value, then list (in a table):

    - SN
    - Purchase Count
    - Average Purchase Price
    - Total Purchase Value




### Most Popular Items

- Identify the 5 most popular items by purchase count, then list (in a table):

    - Item ID
    - Item Name
    - Purchase Count
    - Item Price
    - Total Purchase Value




### Most Profitable Items

- Identify the 5 most profitable items by total purchase value, then list (in a table):

    - Item ID
    - Item Name
    - Purchase Count
    - Item Price
    - Total Purchase Value

## Process
Utilized the Pandas Library and Jupyter Lab to analyze and clean the data.
Various functions and calculations were used in obtaining our data.
Samples of written code:
![Screenshot](Instructions/Screenshots/PurchAnalysis.JPG "Screenshot")
![Screenshot](Instructions/Screenshots/PurchAnalysis2.JPG "Screenshot")


## Results
Several interesting trends were observed after the final analysis of the data sets.

 - Although Female Players make up less than 15% of the total playerbase they spend on average more then male players.
   The biggest spenders on average were players that did not disclose their gender.

 - The largest portion of players are from 20-24 years old but the players that spend the most are 35-39 years old,
   indicating people with a larger disposeable income spend more.

 - The most profitable item was not the most expensive one.  However the most popular item was also the most profitable
   item, indicating that profitability of an item might be linked to its popularity and marketing.