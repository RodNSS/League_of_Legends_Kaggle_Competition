## League of Legends Match Prediction

League of Legends (LoL) is the most widely played multiplayer online battle arena (MOBA) game in the world. Developed by Riot Games and released in 2009, LoL pits two teams of five players against each other. They battle in player-versus-player combat, each team occupying and defending their half of the map.

Each of the ten players controls a character, known as a "champion", with unique abilities and differing styles of play. During a match, champions become more powerful by collecting experience points, earning gold, and purchasing items to defeat the opposing team. In League's main mode, Summoner's Rift, a team wins by pushing through to the enemy base and destroying their "Nexus", a large structure located within. 

In order to match teams of players of similar skill level, LoL groups players into tiers based on their League Points. The tiers are in the following order from lowest to highest:
* Iron
* Bronze
* Silver
* Gold
* Platinum
* Diamond
* Master
* Grandmaster
* Challenger

In this project, you have been given information on 10000 matches played at the Diamond Tier. Based on this data, you will try and predict the winning team of a match based on the chosen champions, each player's experience using their chosen champion, and the first 10 minutes of gameplay from the match.

=======================================

## Here are the steps I took to contribute to my team in order to win the Kaggle competition
https://www.kaggle.com/competitions/ds6-league-of-legends/leaderboard?

1. Created a webscraper to grab player win rates for the given week of the games played.
2. Combined the win rates with other in game stats from the first 10 minutes of each game in order to predict the winner.
3. Used PyCaret to compare and choose the best machine learning model for prediction.
