# Mchezopesa Limited Football-predictive-analysis

![GitHub Logo](football.jpeg)

**Description**

A prediction result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly

Also tasked to figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)

*Approach 1: Polynomial approach*

What to train given:

* Rank of home team
* Rank of away team
* Tournament type

Model 1: Predict how many goals the home team scores.

Model 2: Predict how many goals the away team scores.

*Approach 2: Logistic approach*

Feature Engineering: Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)

**Dataset Columns**

Some features are available on the FIFA ranking page [Link (Links to an external site.)].

Rank
* Country Abbreviation
* Total Points
* Previous Points
* Rank Change
* Average Previous Years Points
* Average Previous Years Points Weighted (50%)
* Average 2 Years Ago Points
* Average 2 Years Ago Points Weighted (30%)
* Average 3 Years Ago Points
* Average 3 Years Ago Points Weighted (20%)
* Confederation
* Date - date of the match
* Home_team - the name of the home team
* Away_team - the name of the away team
* Home_score - full-time home team score including extra time, not including penalty-shootouts
* Away_score - full-time away team score including extra time, not including penalty-shootouts
* Tournament - the name of the tournament
* City - the name of the city/town/administrative unit where the match was played
* Country - the name of the country where the match was played
* Neutral - TRUE/FALSE column indicating whether the match was played at a neutral venue


**Requirements**

Google colab notebook

**Setup instructions**

Save a copy of the notebook in your drive and open it to access.

**Technologies used**

* Pandas Python Library
* Numpy Python Library
* Matplotlib Library
* Seaborn Library
* Sklearn Library

**Bugs**

There were no known bugs are the time of completion

**Support**

In case of any clarifications or suggestions with regards to this project email me at ngolua.kinya@gmail.com

**Licences**

MIT license
