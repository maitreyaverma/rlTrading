# Trading using reinforcement learning
## Environment
There is a gym certified environment as well but has only 2 actions buy and sell. I liked the idea behind that being that the action space should be simple but felt maybe simplifying it more to just long and short would be better. 
Sometimes bots just carry one trade for months (maybe to avoid transaction costs or something else). Asking for a perspective thus is better.

##Future Work
Currently there are only 3 action - long, neutral and short. Would change it to continuous action space. How much percentage long. Would help it understand better. Reward = exp(return) [Seems like a good idea]

##Agent
It is a very simple dqn agent using pytorch. But I dont like the idea of using cnn. Would rather use normal neural network than convolution. Sure shot.