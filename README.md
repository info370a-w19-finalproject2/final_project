# INFO 370 Final Project

Kangwoo Choi, Won Barng, Vincent Widjaya, William Kwok

## Project Description

Sports is an integral part of nearly all cultures. One of the largest sports is football (Soccer. We will refer to it as football). By studying different factors in the data, we can make predictions that many people would be interested in. Team coaches would want to know with data what are the most important factors that lead to a game win. Investors would want to know how likely the team they are sponsoring will do well. Gamblers would like to know gambling trends and what they should bet on. The general public would want to know if their favorite team will win or if there may be illegal match fixing going on with the betting that we cannot see unless we look at the data. As individuals who are passionate about football, we are interested in exploring and predicting outcomes and trying to find hidden patterns.  

For years individuals have tried to use statistics to figure out what makes teams win, or try to find out if their favorite teams are the best. Individuals have tried to use statistics to figure out what makes teams win, or to try to find out if their favorite teams are the best. In fact, “the research for predicting the results of football matches outcome started as early as 1977 by [Stefani R]” (Razali et al).

A study done in 1997 by AJ Lee previously explored the Poisson Regression in an attempt to model team scores to determine if Manchester United was the best team in the Premier League. They predict with some good correlation, but they say their “approach to modeling the scores is a little simplistic. [They] have taken no account of the fact that teams differ from game to game due to injuries, trades, and suspensions. In addition, [they] are assuming that [their] model leads to reasonable probabilities for winning/losing/drawing games".

We can improve on the accuracy by including in our model some of the methods AJ Lee suggested to improve on. It will be difficult to truly predict, as complexity of the game “makes the game result hard to be predicted” (Junyuan Gao) , who also attempted to use a Poisson Regression for her predictions.

We want to test if there is a correlation between: 
* betting odd and actual result.
* between betting odd and game stats.
* between game stats and actual result.

We will be using data from all England Premier League seasons from the 2014/2015 season to the current 2018/2019 season from [Football Data](http://www.football-data.co.uk/englandm.php). This dataset contains data pertaining to the game itself as well as a lot of bets associated with the game. 

We would use the [Poisson Distribution](https://dashee87.github.io/football/python/predicting-football-results-with-statistical-modelling/) for the number of goals by each team. Also, we will try the SGD Regressor and Lasso regression algorithms as suggested by the sci-kit learn algorithm cheat sheet (https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html). In order to select important features in some models, we will use our domain knowledge of football in addition to forward and backward selection.

Our study can be of interest for a number of target audiences. These include soccer fans and followers, soccer betting enthusiasts, as well as investors of soccer teams. However, we will focus on soccer bettors as they would be most interested in the details of our study to maximize their chance of winning. Unlike the other two, bettors’ purpose that is to win bets relate most to ours, that is to find correlations between betting odds, wins, and player/team statistics. 

Some questions our audience could answer from our resource could be:
* What common trends do teams that end up on top have earlier in the season?
* What specific team stats should I focus on watching to maximize my betting odds and rewards?
* Which bookmaker(s) should I bet with that would maximize my rewards?


## Technical Description

## Citations
AJ Lee: https://amstat.tandfonline.com/doi/pdf/10.1080/09332480.1997.10554791

Junyuan Gao: https://www.stat.berkeley.edu/~aldous/Research/Ugrad/Junyuan_Gao.pdf

Razali et al: https://iopscience.iop.org/article/10.1088/1757-899X/226/1/012099/pdf


