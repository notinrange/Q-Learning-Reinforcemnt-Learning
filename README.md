# Q - Learning Using Deep Reinforcement Learning  

Here In this Python Script I tried to Apply Deep Reinforcement learning to Open AI Mountain-Car Enviroment Using gym library of Open AI .

# Q-Learning 
Q-learning is a type of value-based reinforcement learning algorithm that is used to learn the optimal action-selection policy for an agent interacting with its environment. The goal of Q-learning is to learn a function that takes in a state and an action, and returns the expected future reward for taking that action in that state. This function is called the Q-function or the action-value function.

The Q-learning algorithm works by iteratively updating the Q-function based on the agent's experiences in the environment. At each time step, the agent observes its current state, selects an action, and receives a reward and the next state from the environment. The agent then updates its Q-function using the following update rule:

Q(s, a) = Q(s, a) + α * (r + γ * max(Q(s', a')) - Q(s, a))

where Q(s, a) is the current estimate of the Q-function for state s and action a, 
α is the learning rate, 
r is the reward received after taking action a in state s, 
γ is the discount factor, and 
Q(s', a') is the maximum estimated future reward for the next state s' and all possible actions a'.

The Q-learning algorithm continues to update the Q-function in this way until it converges to the optimal Q-function. Once the Q-function has converged, the agent can use it to choose the action that maximizes the expected future reward in each state.



## Code Output


https://user-images.githubusercontent.com/88238469/209535335-7d1b1d9b-ac92-4552-9eb6-210930d11444.mp4

## Episodes Output

![Capture](https://user-images.githubusercontent.com/88238469/209535564-d2568e42-a636-40e4-83be-b9f79b1ad378.PNG)

