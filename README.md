# OpenAI-Gym-CliffWalkingEnv

OpenAI Gym: CliffWalkingEnv
In order to master the algorithms discussed in this lesson, you will write your own implementations in Python. While your code will be designed to work with any OpenAI Gym environment, you will test your code with the CliffWalking environment.



In the CliffWalking environment, the agent navigates a 4x12 gridworld. Please read about the cliff-walking task in Example 6.6 of the textbook. When you have finished, you can learn more about the environment in its corresponding GitHub file, by reading the commented block in the CliffWalkingEnv class. For clarity, we have also pasted the description of the environment below (note that the link below to the Sutton and Barto textbook may not work, and you're encouraged to use this link to access the textbook):

    """
    This is a simple implementation of the Gridworld Cliff
    reinforcement learning task.
    Adapted from Example 6.6 from Reinforcement Learning: An Introduction
    by Sutton and Barto:
    http://people.inf.elte.hu/lorincz/Files/RL_2006/SuttonBook.pdf

    With inspiration from:
    https://github.com/dennybritz/reinforcement-learning/blob/master/lib/envs/cliff_walking.py
    The board is a 4x12 matrix, with (using Numpy matrix indexing):
        [3, 0] as the start at bottom-left
        [3, 11] as the goal at bottom-right
        [3, 1..10] as the cliff at bottom-center
    Each time step incurs -1 reward, and stepping into the cliff incurs -100 reward 
    and a reset to the start. An episode terminates when the agent reaches the goal.
    """

Part 0: Explore CliffWalkingEnv

Part 1: TD Control: Sarsa

Part 2: TD Control: Q-Learning

Part 3: TD Control: Expected Sarsa
