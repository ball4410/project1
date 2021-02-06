# project1

This project was created as a guide to find what kind of breweries and style of beers are most common and in what areas.

Notebook brewery_csv:
Which states have the most breweries?
Looking at the num_breweries_per_state.png, you can see the count of all breweries in each state. This may be used to identify good locations to go to if you're interested in having a lot of breweries to explore. Inwas surprised to see Oregon was not higher on the list. 

Which kind of breweries are most popular?
With the current popularity of craft beers, it is no surprise to see that micro breweries are most abundant. Brewpubs are also very popular as they are more ideal for visits.

Which kinds of beers are most popular?
Once again, no surprise, IPAs dominate the craft beer scene.

What is the difference of ABV in each type of beer?
Anything that is considered a "Double" or "Imperial" is going to have a higher alcohol content. This is evident by looking at the boxplots and seeing how Imperial IPS compare to the other styles.
I found this observation very interesting due the range and oultliers of American IPAs. Is this why IPAs are so popular? Or do they vary so much to satisfy all types of consumers? IPAs are versatile and can be fruit forward and mellow or extremely hoppy and bitter. 

How does ABV relate to IBUs?
There is a positive correlatin between the amount of alcohol by volume and the international bitterness units, however, this does not imply all beers high in ABV are bitter. For example, most bourbon barrel age stouts are high in ABV but do not taste bitter. Their high ABV is due to the amount of malt present in the beer, not hops. 

Notebook open_breweries:
I used open brewery db API to find each kind of brewery in relation to a target city. In my example, the target city was San Francisco and I used the API to return each kind of brewery as well as their latitude and longitude. 

Gmaps was used to then plot each brewery to show where in San Francisco the breweries are located. The idea behind this was, given a city and the list of breweries, where is good central location to stay in order to be near all the breweries you want to explore.
