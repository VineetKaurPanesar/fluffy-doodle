Machine learning, one of the hottest field or technology which is ruling the world. To upgrde our skills, we need to learn these techniques.
As community is getting awared,a high chunk of people are really curious to opt this as their careers. 

So ,while learning ML, training an agent is a significant task. But to help the community and making these tasks more easier here are our projects with efficient coding and appropriate results.

After learning basic types of machine learning i.e, Supervised learning and unsupervised learning, Third level is REINFORCEMENT LEARNING which is based on two rules: 1)- Trial & error method. 2)- Rewards and punishments.
While dealing with reinforcement learning, one need to learn these toy text games too. 

**BRIEF NOTE ON Q-LEARNING**

Q-learning is a machine learning approach that enables a model to iteratively learn and improve over time by taking the correct action. Q-learning is a type of reinforcement learning.
With reinforcement learning, a machine learning model is trained to mimic the way animals or children learn. Good actions are rewarded or reinforced, while bad actions are discouraged and penalized.

With the state-action-reward-state-action form of reinforcement learning, the training regimen follows a model to take the right actions. Q-learning provides a model-free approach to reinforcement learning. There is no model of the environment to guide the reinforcement learning process. The agent -- which is the AI component that acts in the environment -- iteratively learns and makes predictions about the environment on its own.

Q-learning also takes an off-policy approach to reinforcement learning. A Q-learning approach aims to determine the optimal action based on its current state. The Q-learning approach can accomplish this by either developing its own set of rules or deviating from the prescribed policy. Because Q-learning may deviate from the given policy, a defined policy is not needed.

In this, we need to train the model or agent using Q-learning technique, in which we provide environment, and a set of rules on the basis of which agent learns.
In this game, frozen lake an agent is needed to be trained with the help of reinforcement learning using Q-learning.

**ENVIRONMENT DETAILS:-**

The game initializes with the agent at its start state[0,0] of the frozen lake grid and it needs to reach the goal state. The environment grid holds 16 states(4*4=16).
There are holes in the grid of lake which are distributed at diff places and if the agent falls in this  holes, it will recieve a punishment i.e, no rewards or deduction of reward points.
The player will play until  one of these condition comes 1)- it wins , 2)- falls in the hole or 3)- the episode steps are over.

**is_slippery** is an argument which means that an agent  may move perpendicular to the intended direction sometimes ( is_slippery), if you place True in the argument then slippering is a possible condition but if place False agent can't slip.
You can import the environmemt from the following link:-**https://gymnasium.farama.org/environments/toy_text/frozen_lake/
**

**POSSIBLE ACTIONS IN THE GAME:-**

When playing the game you wil notice that the agent is taking 4 possible actions to reach the goal which are listed below:

0: Move left

1: Move down

2: Move right

3: Move up

An agent will take these action to accomplish the task or win the game.

**OBSERVATION SPACE:-**

The observation is a value representing the player’s current position 

The formula used for calculating the observation spaces is **current_row * nrows + current_col (where both the row and col start at 0).**

START STATE:- The initial position of an agent from where it starts the game.

GOAL STATE:- The state in which the goal is achieved and the game ends.

**REWARDS**

This is the vital factor of the game 'rewards'. Any agent learns and hits a trial to get the reward. In this game the reward schedule is:-

Reach goal: +1

Reach hole: 0

Reach frozen: 0

**EPISODE TERMINATION:-**

The episode will be ended under these circumstances:-

a)- Goal is achieved.

b)- Agent falls into the hole.

c)-Episode steps have ended.

Overall,this is the whole working of this game.


