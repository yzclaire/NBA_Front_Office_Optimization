# NBA_Front_Office_Optimization
Optimizing basketball team performance under a salary cap


## Project Goal
Optimize NBA salary cap allocation for a NBA franchise to maximize team performance (winning games) subject to budget constraints imposed by the salary cap.

## Background: 
NBA teams have one goal. They want to win a championship. In order to do that, they want to build the best team by picking the combination of players that increases their odds of winning. They’re constrained by a salary cap which places a limit on the total amount of money they can pay the players on their team. The other team building constraint is each roster must contain at least one player of each of the five main positions (point guard, shooting guard, small forward, power forward, and center). 

Chances of winnings is a variable that we concern. For people who are familar with NBA games probably might know that, there exists player statistics such as win shares, player efficiency rating (PER), and value over replacement player (VORP), are performance scores calculated based on each player's contribution to past games. I am going to model chances of winings uisng these player stats.

## Project plan:
- Problem to solve: Pick NBA players to build a team 
- Objective:  Maximize chances of winnings 
- Constraints:
  * Salary cap : $102M 
  * Roster size : min 8, max 17 
  * Position : at least one player for each of the 5 positions (PG, SG, SF, PF, C)


## Data sources: 
Player salary data: https://www.basketball-reference.com/contracts/players.html 

Player performance data: https://www.basketball-reference.com/leagues/NBA_2019_advanced.html
