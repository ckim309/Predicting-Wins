# About the Project
The NBA (National Basketball Association) can be defined as having 2 distinguished periods during a season. The first, is the regular season which consists of 30 teams that play 82 games, and the second, a postseason tournament called the “Playoffs” to determine the league champion. Prior to the 2019 – 2020 season, teams that finished within the top 8 seeds in their respective conference, the East and the West, were advanced to the Playoffs. However, with the introduction of the “Play-Ins”, only the top 6 teams from each conference advance to the Playoffs while teams that finish the season between 7th and 10th seed compete for the final 4 spots (2 spots in the East and 2 spots in the West). 

This analysis will look at the statistics of an NBA to determine whether the Los Angeles Lakers will achieve enough wins to finish the season within the top 6 places from each conference, guaranteeing the Lakers a spot in the Playoffs. 

The purpose of this project is to create a statistical model that can be used to predict the season record for teams in the NBA. This analysis will look specifically at the Los Angeles Lakers and determine whether they will win enough games to finish the regular season within the top 6 seeds in their respective conference.


# Analysis Summary
The Los Angeles Lakers will not win enough games by the end of the 2022 – 2023 regular season to directly advance to the Playoffs. The team is predicted to win 44 games, 5 games short of the minimum number of games a team in the Western Conference wins to directly advance to the Playoffs. This is due to their low team net rating. Upon further investigating their team net rating, it was discovered that their offensive rating is lower than the league’s average due to their inefficient shooting percentage across 2 pointers, 3 pointers, and free throws. Therefore, the Los Angeles Lakers should look to adjust their offensive game plan to produce more points per possession which will increase their offensive rating, resulting in their overall net rating increasing and winning more games.


![alt text](https://github.com/ckim309/Predicting-Wins/blob/main/Regression%20Model.png?raw=true)

Wins = 39.83787 + 2.40815(NRtg)

## Key Questions
1. How many wins does the Los Angeles Lakers need in the regular season to be guaranteed a spot in the Playoffs?
2. What does it take to win enough games in the regular season to be guaranteed a spot in the Playoffs?
3. Will the current roster of the Los Angeles Lakers achieve enough wins to guarantee them a spot in the Playoffs?
4. Why do the Lakers have a low net rating, and what can they do to win more games?

## Key Insights
1. The Los Angeles Lakers is part of the Western Conference; therefore, they will need to win 49 games to finish within the top 6 seeds to directly advance to the Playoffs.
2. The Los Angeles Lakers need to have a net rating of 4.5 to win 49 games by the end of the season, placing them within the top 6 seeds to directly advance to the Playoffs.
3. The Los Angeles Lakers will not have enough wins to directly advance to the Playoffs for the 2022– 2023 season. The Los Angeles Lakers, with a net rating of 0.6, is predicted to win 41 games by the end of the 2022 – 2023 NBA season, short of the necessary 49 games.
4. The Los Angeles Lakers have a low net rating due to their offensive rating. The Lakers’s offensive rating is ranked 20th compared to the rest of the league because it is taking more possessions to produce points. Despite being ranked 2nd in the number of 2 pointers and free throws made per game, the Lakers are shooting at a low percentage compared to the rest of the league. Also, they are ranked 24th in the number of 3 pointers made per game while having the 5th worst 3 point shooting percentage. Their shooting percentage and offensive tendencies are negatively affecting their offensive rating because less points are being produced per possession. So, adjusting their offensive game plan to produce more points per possession will increase their offensive rating, resulting in their overall net rating increasing. Therefore, the Lakers will win more games.
