# The Big Picture / Overview

The NBA MVP race is usally an exciting race to watch. Being awarded as the NBA MVP for a season is the highest inidividual honor a player can receive. As [Basketball Joe](https://basketballjoe.com/articles/mvp-criteria) points out, every NBA MVP has been inducted into the Hall of Fame. 

The objective of this project is to predict who will be awarded the MVP of the 2019-2020 season using past historical data regarding MVP. This will be determined by looking at the player who has the most amount of votes for the season in reference.

## What type of machine learning problem is this?
I would frame this as regression problem as I am looking to predict the shares of votes each player that played in the season will receive. Can also think of this as a an offline, model-based, supervised (regression) learning system.

## How will performance be measured?
To that end, my main performance measures will be performance measures commonly used for regression problems: `RMSE` and `MAE`

## Expertise Needed
My guy Basketball Joe has a great article about historical MVP voting criteria that I will be using to help guide this project. In his article, he states that there are three branches of MVP criteria: **team success**, **individual statistics**, and **media narratives**. His article provides some key pointers as to what may be the most important features in NBA Voting.

Right before the 1980-81 season the NBA changed its voting method and allowed sportwriters and broadcasters to vote.. 

66% of the league's previous MVPs where awarded from the teams with the best record and 84% of the previous MVPs were awarded from the teams with the two best records. What happens when a team has multiple all stars? Does that hurt these players chances of winning?

*When a team achieves the best record in the league with just one All-Star, the choice for MVP is clear. When a team achieves the best record in the league with 3 or 4 All-Stars, the choice for MVP is not so clear.*

# Getting the Data
For the most robust model, I think I need all the players that played in NBA games from the 1980-81 season to the 2018-19 season. The NBA API allows me to get all career stats for all players. I can the augment this with data from BasketballReference.com.

I will use the players from the 2019-20 season as my test data set.