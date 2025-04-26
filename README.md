# conjoint_analysis
I conducted a conjoint analysis to evaluate the utility scores and relative importance of various attributes (e.g., brand, price, weight, crust, cheese, size, toppings, and spiciness) in determining customer preferences for different pizza profiles. I started by fitting an Ordinary Least Squares (OLS) regression model to quantify the part-worth utilities for each attribute level. Using these part-worth values, I calculated the overall utility score for each of the 16 profiles in the dataset. I used the total range of the part-worths for all levels to calculate the relative importance of the 8 attributes. 

Weight was the most important attribute in deciding which pizza to buy. The most desirable pizza profile was found out to be:  
brand: Oven Story  
price: $4.00  
weight: 100g  
crust: thick  
cheese: Mozzarella  
size: large  
toppings: mushroom  
spicy: extra  
ranking: 16  

To visualize the results, I created a bar chart highlighting the positive and negative utility scores for all 16 profiles, with clear identification of the most and least preferred combinations. This analysis provided actionable insights into the key drivers of customer preferences and helped prioritize features for decision-making.
