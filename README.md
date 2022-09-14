# IPL-match-winning-prediction-of-chasing-team
In this model we predict the winning percentage of chasing team overs by overs.

# Description
- IPL starts in 2008 and till now it was the biggest cricket league in the world.No other league is closed to IPL in terms of revenue and market.
- Within a short period, IPL has become the highest revenue generating league of cricket. Data Analytics has been a part of sports entertainment for a long time. In a cricket match, we might have seen the scoreline showing the probability of the team winning based on the current match situation.This is where data analytic comes in picture.Being cricket fan i enjoyed this model building process. 
- In Machine Learning, the problems are categorized into 2 groups mainly: Regression Problem and Classification problem. The Regression problem deals with the kind of problems having continuous values as output while in the Classification problem the outputs are categorical values. Since the output of winner prediction is a categorical value, the problem which we are trying to solve is a Classification problem.

# Dataset Description
• id: Unique match id.
• date: Date on which the match was played.
• city: Stadium where match was played.
- season: which year tournament is bing played
• battingteam: Batting team name.
• bowlingteam: Bowling team name.
• batsman: Batsman who faced that particular ball.
• bowler: Bowler who bowled that particular ball.
• runs: Runs scored by team till that point of instance.
• wickets: Number of Wickets fallen of the team till that point of instance.
- overs: Number of Overs bowled till that point of instance.
- striker: max(runs scored by striker, runs scored by non-striker).
- non-striker: min(runs scored by striker, runs scored by non-striker).
- Total runs: runs scored by batting first team in first inning of given match.
- Runs left: how many runs left after particular over or ball.
- wicket left: how many wicket was left after particular ball or over.
- Balls left: how many balls left in inning.
- Current score: how many runs have scored by team till that ball or over.
- total: Total runs scored by batting team at the end of first innings.
- rrr:  runs requaried for chasing team to win per over.
- Result: 1 if Chasing team wins  and 0 if chasing team lose.

# Algorithms Used
Logestic Regression
Random Forest Regression
