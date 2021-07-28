# Project_3

## Hypothesis:
### Use a machine learning model to predict the 2021 OPS (On-base Plus Slugging) for the entire roster of MLB players and select a full roster of players with the highest OPS for their salary.

## OPS Background:
### OPS (On-base Plus Slugging) sums a player's on-base percentage and slugging percentage. These two metrics are effectively asking "Does the player get on base?" and "Can he hit?". In summary, how many opportunities does the player create for runs and how successful is he in actually being able to hit? The objective is to utilize a team's offensive statistics to create a lineup with the highest chance of winning. Rather than the traditional scouting approach where there are more qualitative measures of performance such as strength, bat speed, arm extension/follow through, aggression, etc., using these two simple statistics does not require individual analysis of every player and in theory can create a cohesive team by combining compatible players by analyzing their historical performance.

### The OPS formula below:

![OPS](https://blogs.fangraphs.com/wp-content/uploads/2011/04/OBP.png)

### H = Hits - when the batter strikes the ball without error
### BB = Walks - when a pitcher throws four pitches out of the strike zone, none of which are swing at by the batter
### HBP = Hit by pitch - when a batter is struck by a pitched ball without swinging at it and is awarded first base.
### AB = At bat - when a batter reaches base via fielder's choice, hit, or error (not including catcher's interference)
### SF = Sacrifice fly - when a batter hits a fly-ball to the outfield or foul territory that allows a runner to score
### 1B = Single - when batter hits the ball and reaches first base
### 2B = Double - when batter hits the ball and reaches second base
### 3B = Triple - when batter hits the ball and reaches third base
### HR = Home run - when batter hits the ball and circles all four bases

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
