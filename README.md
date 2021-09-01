# Surf and Shake Shop in Oahu Analysis
## Overview
- I recently traveled to Oahu and fell in love with it- who wouldn't?! I loved surfing and relaxing on the beach so my first thought was: "How can I stay here permanently and sustain a life here?". My plan was to open a Surf and Shake Shop on the beach to be close to the place I love most- and to do that I would need the help of an investor. I did some analysis into temperatures and rainfall in the months of June and December to see if this business plan was viable. Below is my statistical analysis with results about my future business endeavor- spoilers: pick out your favorite flavor shake while you're going through my analysis :)

## Results
### June Analysis
- I first started with gathering weather data from the past 8 years in a SQLite file, importing it into a Pandas DataFrame and performing analysis on it to get some summary statistics for the month of June. That figure is shown below:

<img width="300" alt="June_temps_table" src="https://user-images.githubusercontent.com/86524863/131727025-58563a43-9190-4698-a727-9b75ec087008.png">

- This table shows temperatures in the month of June across the 8 years of data, and as we can see June is a great month for surfing and sun. The average temp in June is 75F with a lower quartile (25%) temperature of 73F and upper quartile (75%) of 77F. This would definitely lend itself to needing a refreshing shake on the beach after some surfing in the ocean. This is great news but lets check out one of the coldest months next- December.

### December Analysis
- Using my SQLite file and Pandas I also did an analysis on the data from December, that table is shown below:

<img width="343" alt="Dec_temps_table" src="https://user-images.githubusercontent.com/86524863/131727791-41f498cf-c400-485a-acef-a4c0e928f979.png">

- Using this table we can deduce that Decembers temperatures aren't too much colder than Junes. The average temperature for the month over 8 years is 71F, still very warm for a winter month. Oahu is close to the equator so this does make sense geographically but doing the analysis gives me and my future investor hard data to back up our business venture. A difference of only 4F isn't enough to close down shop and hurt our business profits. This is great news!

## Summary
- To more easily visualize the relationship of temperatures in June vs December, I created a line graph showing average temps for each month by year, that image is shown below:

![June_Dec_Temp](https://user-images.githubusercontent.com/86524863/131729245-1e6ab45b-a337-42aa-a408-fb7441ff315b.png)

- As we can see by the graph, the temperatures are plenty warm enough even in winter months to enjoy the beach and a delicious milkshake. 
- Temperature has been checked and verified to not be an issue- but what other weather could potentially put our business at risk- rain. No one likes to be on the beach drinking a shake in the rain, so I decided to take my data and do some analysis into average precipitation during the months of June and December. 
- I took our 8 years of weather data and grouped them by precipitation and plotted the average rainfall on a graph to easily visualize how much rain one can expect in Oahu in the summer vs the winter. The graph is shown below:

![June_Dec_prcp](https://user-images.githubusercontent.com/86524863/131729416-a4575f00-b951-44f9-b198-bf5088e1e96d.png)

- The precipitation graph shows that 2010 was an outlier year with over 0.4 inches of rain, but every other year shows about 0.2 inches or lower for every other year in our data. 0.2 inches or lower for the whole month is not enough rainfall to make me nervous about the business. If 1 out of every 8 years we have double the rainfall and that's still only slightly over 0.4 inches, I'd say that our shop could stay open for most of the month without fear of rain causing business to be slow or us to have to close down. 

## Conclusion
- After doing the data analysis I feel very confident that my business idea would work in Oahu! The average temperature is high enough in both summer months and winter, and the rainfall is minimal and wouldn't cause the shop to suffer due to inclement weather. All that's left now is to present my data to an excited investor, pack my bags, and start picking out shake flavors for my menu!

**My favorite flavor of shake is vanilla with Oreo by the way, best combo!**


