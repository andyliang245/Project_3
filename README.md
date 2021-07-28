# Project_3

## Hypothesis:
### Use a machine learning model to predict the 2021 OPS (On-base Plus Slugging) for the entire roster of MLB players and select a full roster of players with the highest OPS for their salary.

## OPS Background:
### OPS (On-base Plus Slugging) sums a player's on-base percentage and slugging percentage. These two metrics are effectively asking "Does the player get on base?" and "Can he hit?". In summary, how many opportunities does the player create for runs and how successful is he in actually being able to hit? The objective is to utilize a team's offensive statistics to create a lineup with the highest chance of winning. Rather than the traditional scouting approach where there are more qualitative measures of performance such as strength, bat speed, arm extension/follow through, aggression, etc., using these two simple statistics does not require individual analysis of every player and in theory can create a cohesive team by combining compatible players by analyzing their historical performance.

### The OPS formula below:

![OPS](https://blogs.fangraphs.com/wp-content/uploads/2011/04/OBP.png)


## Model:
### Long Short-term memory, recurrent neural network

## Data and Parameters:

### Data: 
#### Used MLB historical game/player data from 2010 through 2020
#### 2021 player salaries
#### Dropped any players if they had an OPS of 0 in the year they played

### Model Training:

### Model Performance Evaluation:

### Variables: -
