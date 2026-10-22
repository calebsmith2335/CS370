# CS370
Project Overview

This project involved developing a pirate intelligent agent that learns to navigate a maze and find treasure. It demonstrates how reinforcement learning and neural networks can work together to solve a pathfinding problem. The agent learns through interactions with its environment, using rewards and penalties to improve its decisions.

The provided starter code included the maze environment, supporting functions for tracking experiences, and a framework for building and testing the neural network. My primary contribution was completing the deep Q-learning training algorithm in the Jupyter Notebook. This included implementing the training loop, balancing exploration and exploitation, collecting experiences, and using those experiences to train the model. I also evaluated the agent’s performance to determine whether its learned strategy could successfully reach the treasure.

What do computer scientists do, and why does it matter?

Computer scientists analyze problems and develop computational solutions using algorithms, software, and data. Their work involves understanding a problem, selecting appropriate techniques, testing results, and improving the reliability and efficiency of a solution. This matters because software affects how people work, communicate, access services, and make decisions.

This project helped me understand how an intelligent system can learn a strategy instead of relying on a programmer to specify every move. Similar concepts can support applications such as robotics, route planning, and automated decision support, although each application requires its own design and testing.

How do I approach a problem as a computer scientist?

I approach a problem by defining the goal, identifying constraints, and breaking the work into smaller tasks. For the pirate agent, this meant understanding the maze, the available actions, and how rewards influenced learning. I then implemented the training process, examined its behavior, and used the results to guide improvements.

Throughout this course, I learned that choosing the right algorithm and preparing appropriate data are just as important as writing code. I also learned to distinguish performance during training from performance in testing. A model needs to demonstrate that it can handle the situations it is expected to encounter, rather than simply perform well on familiar examples.

What are my ethical responsibilities to the end user and the organization?

My ethical responsibilities include protecting sensitive information, testing software carefully, communicating limitations, and considering how errors or biased results could affect people. Users and organizations need accurate information about what a system can do so they can make informed decisions about relying on it.

This project also showed me that the reward structure influences an agent’s behavior. Developers must consider whether the behavior a system is encouraged to learn actually supports the intended goal. In workplace applications, I would also prioritize appropriate human oversight, clear accountability, and ongoing evaluation. A successful solution should be useful and reliable while respecting the people affected by it.
