# BarBeerDrinker

A web application built with Python, Flask, and Angular. The relational database created and queried with MySQL. Shows bars, beers, drinkers, and their transactions in NJ and the tri-state area, with abilitiy to view queries such as the most popular beers in a bar, or the most frequented time of day. 

Several tens of thousands of transactions were created with transaction ID, date, time, bar, drinker, price, tip, list of items bought. These can be viewed in the aggregate or interacted with to find the most common bars, beers, and drinkers for each category, as well as time of day, months, quantity, and total costs of these cumulative transactions. Drinkers have a list of likes as well, so that they only like specific bars and beers.  

The data was first generated, with hundreds of thousands of transactions, and then only transactions which meet the following patterns were selected:
 - drinkers only frequent bars they like
 - drinkers only purchase beers they like
 - drinkers only frequent bars in the same state as them
 - transactions can only be issued during a bar's open hours
 - beers can vary in price from bar to bar, but remain consistently more or less expensive than their fellow beers
     * if Stella Artois is $5 and Bud Light is $3 in one bar, Stella must cost more than $6 in a bar where Bud Light is $6

And examples of web app's pages, and the queries that can be automatically viewed: 

![Home](https://github.com/ggdurrant/BarBeerDrinkerGroup67/blob/master/images/homePage.JPG)

![Bar1](https://github.com/ggdurrant/BarBeerDrinkerGroup67/blob/master/images/bar1.JPG)

![Bar2](https://github.com/ggdurrant/BarBeerDrinkerGroup67/blob/master/images/bar2.JPG)

![BeerHome](https://github.com/ggdurrant/BarBeerDrinkerGroup67/blob/master/images/beerHome.JPG)

![Beer1](https://github.com/ggdurrant/BarBeerDrinkerGroup67/blob/master/images/beer1.JPG)

![Drinker1](https://github.com/ggdurrant/BarBeerDrinkerGroup67/blob/master/images/drinker1.JPG)

![Drinker2](https://github.com/ggdurrant/BarBeerDrinkerGroup67/blob/master/images/drinker2.JPG)
