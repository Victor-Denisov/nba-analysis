# NBA Analysis
"Hey you're tall, you should be good at basketball right?"

I'm sure that many tall people heard this at least once in their lives. Usually,
the response is that they either haven't played enough to know, or laugh it off, or some may
say that height has nothing to do with basketball skill.

It's a well known fact that human height is a normal distribution, but how does height
compare to a basketball player's ability to score? This is the question that I would like to
analyze and solve using the NBA's publicly available API.
https://github.com/swar/nba_api

--------
### Project Files

The project is coded in python using a jupyter notebook named: NBA-Analysis.ipynb 

There are several required libraries needed to run the notebook prior to running the notebook, 
however most are well-known in the industry.

Relevant images are in the images folder

--------
### Project Summary
Using a basic regression model, there is a linear relationship between field goal attempts (FGA) and points per game(PPG) but no clear relationship between height and ppg
![fgappg](https://raw.githubusercontent.com/Victor-Denisov/nba-analysis/main/Images/fga%20vs%20ppg.png "fga vs. ppg") ![heightppg](https://raw.githubusercontent.com/Victor-Denisov/nba-analysis/main/Images/height%20vs%20ppg.png "height vs. ppg")

Height has a better relationship to the number of rebounds and the number of blocks achieved per game
![heightrebounds](https://raw.githubusercontent.com/Victor-Denisov/nba-analysis/main/Images/height%20vs%20blocks.png "height vs. rebounds") ![heightblocks](https://raw.githubusercontent.com/Victor-Denisov/nba-analysis/main/Images/height%20vs%20rebounds.png "height vs. blocks")

--------
### Assumptions and Other Considerations
There are a few flaws with this methodology. For example, I am only using one season of data to achieve these conclusions.
Ideally, I should be using a larger data set of 20+ seasons (or more) to determine whether the identified trend applies over time.
I am also using anecdotal bias in my own experience with watching the NBA to understand that height likely is better
correlated to rebounds and blocks and did not explore other data available. 

The purpose of this analysis was to use the NBA API to do a quick analysis of an NBA player's height and understand if 
height has a relationship to PPG. This analysis could be further enhanced by analyzing all statistics collected during a game
to better understand the correlations of height and which aspects of the game that height effects the most.