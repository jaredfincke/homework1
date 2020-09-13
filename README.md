# Homework 1
First homework due 9.17.2020

In ReadMe, explain briefly your project, your goals and methods. Also explain how and where did you get the data. Finally in ReadMe you should describe how a potential reader should navigate in this Github Repo.

## Overview
Major League Baseball has existed for almost 150 years. Largely, the rules of the game have remained consistent, however strategies have changed. The goal of my project is to show how pitching in particular has changed through the years. I believe today's starting pitchers are ptiching less innings per game in an effort to preserve their arms from being injured. My hypothesis is that the number of complete games per season, a stat indicating a pitcher has pitched all innings of the entire game, has decreased over time. If pitchers are less frequently completing the whole game, I am interested if that has resulted in fewer wins per season, and a lower Earned Run Average.

## Method
I only included starting pitchers, that is pitchers' seasons  whose Games Started (GS) is equal to Games Played (G). I also exlcuded pitchers who were unable to record a single out for their season, since calculating an Earned Runs Average (ERA), calculated by Runs over Total Outs Pitched, is impossible without any outs. 


## Sources
The dataset came from Kaggle's Baseball Databank. I only used the "Pitching" file, which includes over 44,000 pitchers' seasons and their statistics from 1871 to 2015. The recorded statistics used for this project were Player, Year, Team, Wins, Losses, Games, Games Started, Shut-outs, Innings/Outs Pitched, and Earned Run Average. 
https://www.kaggle.com/open-source-sports/baseball-databank This is the Kaggle I got my data from. 



## How to navigate my Github Repo
The data can be found in the "Data" directory. There is a raw data file and a cleaned data file. 
Only a single Jupyter notebook was used to clean the data and to analyze it. The results are also found