# BlackJackAI
CS 4664 Final Project Deliverable:
Tommy Billington, Kenneth Hsu, & Ajay Kanjoor

This goal of this project was to create a RL based approach to making money from Blackjack. While perfect blackjack can be attained through algorithmic design, our goal was to play the game at a very high level while also making use of card counting to make sure that the hands we did win, we won them with higher bets. To test this approach we ran three different experiments with three different card counting strategies. 

## Installation:
Requires matplotlib, random, and numpy.

## Code:

### HiLo.ipynb: 
Contains the basic version of card counting where you add a score of +1/-1 for high and low cards. 

* Blackjack class - Contains development of environment, i.e. decks, rules, etc.
* QLearningAgent class - Contains the hyperparams and HiLo betting strategy of the RL agent

### HiOptII.ipynb: 
Contains a level 2 card counting strategy, HiOptII.

* Blackjack class - Contains development of environment, i.e. decks, rules, etc.
* QLearningAgent class - Contains the hyperparams and HiOptII betting strategy of the RL agent
  
### WrongHalves.ipynb: 
Contains a level 3 card counting strategy, WrongHalves.

* Blackjack class - Contains development of environment, i.e. decks, rules, etc.
* QLearningAgent class - Contains the hyperparams and WrongHalves betting strategy of the RL agent

## Conclusions:

HiLo: 
* Very efficient win/loss ratio
* High total and average return over multiple testing iterations
* Overall, high-potential model for goal of monetary gain
* Could improve card counting strategy to maximize return

HiOptII:
* Incredibly similar to Hi-Opt 1 method counting.
* Higher level doesn’t mean better, just alternative

WrongHalves:
* Noticeable and significantly more ties then other two methods
* More complex card counting with zero errors can effectively make more profit
* Would never be worth the change for real humans.

Overall:
All three card counting strategies seemed to be very variable, as expected with games of chance. However, overall, the WrongHalves method was slightly more efficient than HiLo and HiOptII due to its increased complexity. All in all, this model shares promising insights into how RL can be utilized for games such as BlackJack to bridge the gap between the casino and the player. 
