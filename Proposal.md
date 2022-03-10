# COMP3106 Project Proposal - A Xiangqi Game AI

### Team Member 

Ou Junyi - 101080112 

Ma Di - 101103827

### The Game

Xiangqi, also called **Chinese chess** or **Elephant chess**, is a strategy board game for two players. It is in the same family of games as Western chess. The pieces are placed on the intersections, which are known as *points*. Each player has 16 pieces to start with, and just like Western chess, different pieces are allowed to perform different actions under s set of rules. 

Our goal is to build an AI capable of playing against and winning human players to a certain level. The game of Xiangqi is known as static, episodic, and fully observable. 

### The Method

We are planning to implement a Monte-Carlo search tree and use a neural network to guide the playout policy. A Xiangqi game usually has a branching factor of around 50, and it is very hard, even for today's computer, to exhaust all the possibilities. Hence we are planning to use a neural network to rule out our playout policy, and we will create a model with training on our local machine. 
