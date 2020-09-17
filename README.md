# Pitching Analysis Over Time

## Overview
Major League Baseball has existed for almost 150 years. Largely, the rules of the game have remained consistent, however strategies have changed. The goal of my project is to show how pitching in particular has changed through the years. I believe today's starting pitchers are ptiching less innings per game in an effort to preserve their arms from being injured. My hypothesis is that the number of complete games per season, a stat indicating a pitcher has pitched all innings of the entire game, has decreased over time. If pitchers are less frequently completing the whole game, I am interested if that has resulted in fewer wins per season, and a lower Earned Run Average.

## Method
I only included starting pitchers, that is pitchers' seasons  whose Games Started (GS) is equal to Games Played (G). I also exlcuded pitchers who were unable to record a single out for their season, since calculating an Earned Runs Average (ERA), calculated by Runs over Total Outs Pitched, is impossible without any outs. Once I wrangled data, 


## Sources
The dataset came from [Kaggle's Baseball Databank](https://www.kaggle.com/open-source-sports/baseball-databank). I only used the "Pitching" file, which includes over 44,000 pitchers' seasons (rows) and their statistics from 1871 to 2015. The recorded statistics used for this project were Player, Year, Team, Wins, Losses, Games, Games Started, Shut-outs, Innings/Outs Pitched, and Earned Run Average. To wrangle and analyze the data I imported the Pandas Data Analysis Library for Python. 



## How to navigate my Github Repo
The data can be found in the "Data" directory. There is a raw data file and a cleaned data file. 
There are also two Jupyter notebooks. One notebook named "Code - Other Notebook" shows how I was able to wrangle the data. The one labeled "Technical Notebook" is where I performed my analysis on the data . 