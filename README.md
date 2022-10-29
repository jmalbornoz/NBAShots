# NBAShots
A model to predict the outcome of shots in the NBA

The business use case addressed in this notebook is related to sport analytics and scientific betting (if you want to know more about this area, please have a look at [The Perfect Bet, by Adam Kucharski](https://www.amazon.co.uk/Perfect-Bet-Science-Taking-Gambling/dp/0465055958))

We will consider **NBA basketball games** - we are interested in predicting the outcome of a shot taken by a player: **will the shot be made or will it be missed?** 

* Can we consistently predict the outcome of a shot?
* What are the factors that determine if a shot will be made?

Answering these questions may lead to a profitable automated betting strategy.

We are also interested in gaining insights that can inform how players in a team could be selected  for maximum performance (as well as informing possible game strategies) by answering the following questions:

* Are there players who are consistently effective at making shots?
* Are there players who are consistently effective at preventing shots from being made?
* Are there combinations of teams in a game in which one of the teams is consistently good at making shots? This could be an indication not only of individual player performance but team performance.
* Are there combinations of teams in a game in which one team is consistently good at preventing shots from being made? Again, this could be an indication not only of individual defenders' performance but team performance.
* Are there any other insights that could complement our domain knowledge?

In order to address the above questions, we have a dataset for a series of NBA games containing player-by-player information; the dataset describes attempted shots and the outcome (made/missed) together with other factors that may influence the outcome of the shot. 

The data used to create the dataset is freely available and can be downloaded from [https://www.nba.com/stats](https://www.nba.com/stats)
