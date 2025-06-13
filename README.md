# Project 1 [ The Management of Museums ](https://github.com/sitimustikaayu/portfolio/blob/main/Museums.ipynb)
Manage the museums in the City of Los Angeles
![ex1_museums](https://storage.googleapis.com/kaggle-media/learn/images/pFYL8J1.png)

Data from the Los Angeles [Data Portal](https://data.lacity.org/) that tracks monthly visitors to each museum.  

## Summary Insight

- ### Convince the museum board 
![image](https://github.com/user-attachments/assets/370409ea-a241-42d9-8f38-4053d04b3a2c)
The Firehouse Museum claims they ran an event in 2014 that brought an incredible number of visitors, and that they should get extra budget to run a similar event again.  The other museums think these types of events aren't that important, and budgets should be split purely based on recent visitors on an average day.
Key Observations:
- Avila Adobe consistently had the highest number of visitors compared to the other museums, with noticeable fluctuations but generally ranging between 15,000 to over 40,000 visitors per month.
- Firehouse Museum shows a significant spike in late 2014, reaching over 60,000 visitors in a single month — much higher than any other data point. After that, its visitor numbers dropped and remained relatively stable at a much lower level.
- Chinese American Museum had the lowest visitor numbers, mostly staying below 5,000 visitors per month, showing relatively stable but low traffic.
- America Tropical Interpretive Center had moderate and fairly consistent visitor numbers, mostly between 4,000 to 12,000 visitors per month, with some small fluctuations over time.

- ### Assess seasonality
![image](https://github.com/user-attachments/assets/c8a36f1e-c767-4630-a532-1ac66c6bc05c)
When meeting with the employees at Avila Adobe, one major pain point is that the number of museum visitors varies greatly with the seasons, with low seasons (when the employees are perfectly staffed and happy) and also high seasons (when the employees are understaffed and stressed). You realize that if you can predict these high and low seasons, you can plan ahead to hire some additional seasonal employees to help out with the extra work.
Key Observations:
- 2014 to mid-2015: Visitor numbers fluctuated significantly, often ranging between 20,000 to over 35,000, with several sharp peaks. The highest point occurred around mid-2015, reaching over 40,000 visitors in a single month.
- 2016 to 2017: Visitor counts began to stabilize, showing a more regular up-and-down pattern but with a slight downward trend overall. Monthly visitors mostly stayed between 15,000 to 30,000.
- 2018: A noticeable decline is observed. Visitor numbers consistently dropped to below 25,000, reaching some of the lowest points in the entire period by the end of 2018.

## Recommendations & Next Steps  
- Avila Adobe was the most popular site during this time period, while the Chinese American Museum attracted the fewest visitors. The spike in the Firehouse Museum data could indicate a special event or data anomaly in late 2014.
- Avila Adobe usually gets more visitors in March-August (or the spring and summer months). With this in mind, Avila Adobe could definitely benefit from hiring more seasonal employees to help with the extra work in March-August (the spring and summer)
- The Avila Adobe museum experienced strong visitor interest in the early years (2014–2015), but over time, attendance gradually declined. This may suggest changing public interest, reduced promotions, seasonal factors, or external influences affecting tourism. The trend highlights the importance of engagement strategies to maintain or grow museum attendance.



# Project 2 [Create Own Video Game](https://github.com/sitimustikaayu/portfolio/blob/main/IGN.ipynb)
![ex2_ign](https://storage.googleapis.com/kaggle-media/learn/images/Oh06Fu1.png)


### Which platform is best?
Based on the data, Xbox One seems to be the best alternative, since it has the highest average ratings.
![image](https://github.com/user-attachments/assets/0489b42b-514a-4071-8db2-eb0047cb986a)


### Which combination of genre and platform receives the highest average ratings? Which combination receives the lowest average rankings?
Simulation games for Playstation 4 receive the highest average ratings (9.2). Shooting and Fighting games for Game Boy Color receive the lowest average rankings (4.5).
![image](https://github.com/user-attachments/assets/324a08d5-7d57-429f-89d6-0a790e5b7dff) 

## Business Metrics
- Average Review Score by Platform and Genre.
- Highest-rated Platforms based on average scores across all genres.
- Most Popular Genres with consistently high ratings across platforms.
- Heatmap to identify genre-platform combinations with strong review performance.

## Summary Insight
Based on IGN review data:
- Platform Performance: The PlayStation 4, Xbox One, and PC platforms tend to have higher average review scores, suggesting better quality or broader appeal of games on those systems.
- Genre Trends: Genres like Action, Shooter, and Role-Playing show consistently high ratings, making them strong candidates for new game development.
- Weak performers include platforms with low market share or mobile-focused systems, which typically received lower average scores.

## Recommendation 
- Develop your game for one of the top-rated platforms such as PS4, Xbox One, or PC to increase the likelihood of positive reception.
- Focus on high-performing genres like Action or RPG where player expectations are well-established and positive.
- Benchmark against top-rated games in your selected platform/genre to identify key quality features (graphics, story, multiplayer features).

## Conclusion
This data-driven analysis of IGN review scores reveals clear trends that can guide successful game development. Platforms and genres with historically higher ratings should be prioritized to maximize both critical and player acclaim. By leveraging these insights, you can make strategic design decisions aligned with proven market preferences.

# Project 3 : [The Sweet Spot: Using Data to Guide Candy Product Design ](https://github.com/sitimustikaayu/portfolio/blob/main/candy.ipynb)
## People have a slight preference for candies containing relatively more sugar
![image](https://github.com/user-attachments/assets/1efa5543-3831-4fee-a8cf-038afcc7ad37)

## Price sensitivity is different depending on the presence of chocolate
![image](https://github.com/user-attachments/assets/a56e2073-043e-421c-80bf-88b8474e3acd)
- ### Higher-priced chocolate candies can still be well-liked, but non-chocolate candies should be priced more competitively to maintain popularity
- ### This supports a segmented pricing strategy based on product content

## Chocolate is a strong positive factor in consumer preference
![image](https://github.com/user-attachments/assets/16c94c23-c965-4cb9-a687-212fed4dea57)

## Business Metrics
- Win Percent: A proxy for popularity based on a survey — the higher the percentage, the more preferred the candy.

- Sugar Percent: Indicates the relative sugar content of a candy.

- Price Percent: Indicates how expensive a candy is compared to others.

- Categorical Attributes: Chocolate, fruity, caramel, and other properties describe the candy composition.

## Summary Insight
- A scatter plot shows a positive correlation between sugarpercent and winpercent, implying that candies with higher sugar content tend to be more popular.

- Candies such as ‘3 Musketeers’ are more popular than ‘Almond Joy’, while ‘Air Heads’ have more sugar content than ‘Baby Ruth’.

- The dataset allows visual examination of consumer preferences tied to sugar levels and candy types.

## Recommendation
- Focus on producing candies with moderate-to-high sugar content to increase consumer appeal.

- Incorporate chocolate elements where feasible, as chocolate candies tend to have higher popularity in general.

- Consider benchmarking new products against top performers like "3 Musketeers" based on the winpercent metric.


## Conclusion
Through data visualization using scatter plots, we discovered that sugar content plays a significant role in candy popularity. Future product development should strategically align sweetness and pricing with consumer preferences to enhance success in the competitive confectionery market.





