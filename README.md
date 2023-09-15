# SC1015_NBA
# SC1015 Project


Practical Motivation and Sample Collection

We as a group are very interested in basketball and the NBA and thus, we felt that it would be interesting to analyse the NBA All-Star game and the home-court advantage present in the NBA

Sample Collection
NBA Stats 2016-2019 - https://www.kaggle.com/datasets/toniabiru/nba-stats-20162019-seasons
NBA Stats 2020-2021 - https://www.kaggle.com/datasets/toniabiru/20202021-season-stats
Games.csv - https://www.kaggle.com/datasets/nathanlauga/nba-games?select=teams.csv 
Basketball Reference NBA Summary - https://www.basketball-reference.com/leagues/NBA_2022.html#all_confs_standings_E 


Problem Formulation:

Problem 1:  What variables are important to predict NBA All-Stars and is it possible to predict the NBA All-stars for future seasons?
Problem 2: How effective is Home court advantage

## Problem 1: Analyzing NBA All-Star Selection Factors using Predictive Modeling

Aim is to find out what statistics are important for a player to be considered an All-Star and the main variables used are Rebounds, points, win share and assists.

For Exploratory Data Analysis, we compared the average statistics of nba players in the nba with that of the all-stars and also, shows the correlation of these varibales with All-Star using a heatmap.

Next in machine learning, we utilized Random forest to create a model for our prediction. We created 2 models, one with all the variables, and one without the unecessary ones that have a low correlation with All-Star. It was found that the second model had a higher prediction accuracy and thus, we used that to predict the nba all-stars for the 2020-2021 season.

Inference:
Out of all the variables, Win Share proved to be the most effective as it had the highest correlation with All-Star. 
Our approach, however, could be improved if it took into consideration the votes of fans, players, and managers. This is due to the fact that voting is a factor in selecting whether or not a player is an All-Star.

## Problem 2: Evaluating Home Court Advantage in Team Win Percentages
### (Part 1 file is titled: Home Court Advantage (Effectiveness) )

Aim is to find out whether home court advantage is effective in determining the win percentage of all individual teams.

For Exploratory Data Analysis, we compared the points scored by home and away teams, computed the difference in their points from the perspective of home teams, and explored its effectiveness.

In machine learning, we created 2 multivariate regression lines including other factors points, based on 2 equations we came up with.

Inference: 

We found out that the mean squared error and root-mean-square error decreased slightly without the implementation of home-court advantage. We also realised home court advantage on its own does have a significant impact. However, when placed alongside crucial factors, it does not become as effective. In the end, there are still other factors to take note of such as the crowd, the noise, whether the players are recovering from injuries

Contributions:

Introduction and Problem 1 - Anathan Srinath Adhvait (U2121974B)
Probem 2 - EDA and Analytics Exploration - Wan Kai Jie (U2120427H) 
           Machine Learning and Statistical Inference - Anapana Dinesh Kumar (U2122938K)

Slides and Script - Everyone
