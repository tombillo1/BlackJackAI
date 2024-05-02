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

## References: 
[1] Blackjack: Reinforcement Learning Approaches to an
incomplete ..., https://www.researchgate.net/profile/AkinWilson/publication/338992214_Blackjack_Reinforcement_Le
arning_Approaches_to_an_Incomplete_Information_Game/l
inks/5e 37fd56a6fdccd96582255d/Blackjack-ReinforcementLearning- Approaches-to-an-Incomplete-Information-Game.
pdf.
[2] T. Vos, “Reinforcement learning and evolutionary algorithms in the stochastic environment of Blackjack,” Student
Theses Faculty of Science and Engineering, https://fse.student
theses.ub.rug.nl/27515/.
[3] J. Colten, “Can you beat the odds? A reinforcement
learning approach to optimal policy search in Blackjack,”
repository.arizona.edu, https://repository.arizona.edu/handle
/10150/668571.
[4] Beating blackjack - A reinforcement learning approach
- stanford university, https://web.stanford.edu/class/aa228/rep
orts/2020/final117.pdf.
[5]“Card Counting - Strategie

Overall:
All three card counting strategies seemed to be very variable, as expected with games of chance. However, overall, the WrongHalves method was slightly more efficient than HiLo and HiOptII due to its increased complexity. All in all, this model shares promising insights into how RL can be utilized for games such as BlackJack to bridge the gap between the casino and the player. 
