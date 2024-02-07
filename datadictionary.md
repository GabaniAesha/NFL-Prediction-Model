NFL Prediction Model

*** Final Dataset Column Dictionary *****
schedule_date - Games when they were scheduled and played
schedule_season - Game year(>=1979)
schedule_week - Weeks from 1 to 21 when the games were played
team_home - List of 32 NFL Teams 
score_home - Home team scores
team_away - Away teams that played against Home teams on specified dates
score_away - Away scores 
team_favorite_id - Teams that were favoured 
spread_favorite - margin of points for the favored team(refers to the team that is favored to win a game by a certain margin of points)
over_under_line - refers to a betting line that predicts the total number of points that will be scored in a game by both teams combined
stadium - Stadium names
stadium_neutral - If the games were played in neutral stadiums then 1 else 0
weather_temperature
weather_wind_mph
fav_home - list of only Home favourite teams
fav_away - list of only Away favourite teams
over - 1 if score_home + score_away is greater than over_under_line else 0
team1 - Elo Home team names
team 2 - Elo Away team names
elo1_pre - Pre points of home team 
elo2_pre - Pre points of away team
elo1_prob - Probability of winning of home teams
elo2_prob - Probability of winning of away teams
elo1_post - Post game points of home team
elo2_post - Post game points of away team
result - 1 if home team scores are greater than away team scores else 0



