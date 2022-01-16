# pandas-challenge
This is the commit for the Pandas Challenge homework. I have chosen to complete the Heroes of Pymoli portion!

The code for this challenge will read through the given data, the "purchase_data.csv" file. This file contains individual purchase records for in-game items for a fantasy game. 

First, we will import the file and read it, showing a preview of the data.
Next, we will find and display the total number of individual players. This takes into account that one player may have multiple purchase lines.
Then we will analyze the purchases:
    find the number of unique items available
    the average price per item
    the total number of purchases
    and the total revenue

Next, we analyze the gender demographics of the players. This is when we start grouping the original data. We group the data by gender so that we can do our analyses on each group all at once, as opposed to having to create individual dataframe (what I did first and then realized it was more complicated than necessary).
    Once grouped, we find the total number of players per gender
    and the percentage each gender makes up of the whole
    
    Next we find the total purchases, the average purchase price, the total purchase price, and average total purchase amount per gender

After gender, we move to age demographics. Here, instead of grouping right away, we create bins based on age ranges. Then, once all the players have been categorized by age range bins, then we group by those ranges.
    From those ranges we find the total number of players
    the percentage each makes of the whole
    the average purchase price
    the total purchase value
    and the average total purchase per player

After age we move to individual player spending habits. Here we go back to grouping the whole dataset and do it by screen name. From here we take the same data points:
    total purchases
    average pruchase price
    total purchase value

Lastly, we analyze the in-game items themselves. Here, we first create a new dataframe from all the item data we already have (Item ID, Name, and Price). Then we group that data by the ID and Name. After that, we get our data points:
    total purchase of each item
    total purchase value
    item price
    Then we sort it by the top 5 most purchased items

    Lastly, we find our 5 most profitable items.
    We do this by sorting our item data by the 5 items with the highest total purchase value.

And we're done! Thank you for reading my novel and for checking out my code. I felt good about this assignment, especially after figuring out the groupby's. Definitely made the code much cleaner and simpler!