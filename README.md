# deep-Q-learning-pirate-agent

Deep Q-learning intelligent agent for a pirate treasure hunt game, developed for SNHU CS 370.

## Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

Most of the code was already provided to me. My goal was to complete the Q-training algorithm so the agent could learn the best possible way to get to the treasure, preferably before reaching the 1,000-epoch limit. The code provided included `TreasureMaze.py`, which was the actual maze environment and included obstacles, movement, and rewards. Also provided was `GameExperience.py`, which stores the agent's experiences so the agent can learn from previous actions. The code I completed was within the provided `TreasureHuntGame.ipynb`, which was the starter Jupyter Notebook containing the neural network setup, helper functions, and the incomplete Q-training algorithm. My code implemented the deep Q-learning training loop in `qtrain()`, which used both exploration and exploitation to help the pirate choose what actions to take. The agent's experiences were stored and then used to train the neural network. I had my code update the target network periodically and adjust the exploration during training so the amount of random moves decreased. Finally, I tested whether the pirate could successfully find the treasure. The agent reached a 100% win rate over recent games at epoch 354 and passed the completion check, confirming it could successfully reach the treasure from all valid starting positions.

## What do computer scientists do and why does it matter?

Computer scientists solve problems using algorithms, programming, and computational systems. They do so by designing, developing, testing, and improving solutions. Their work affects nearly every industry, especially as technology is relied on more heavily to carry out day-to-day tasks.

## How do I approach a problem as a computer scientist?

I approach a problem as a computer scientist by starting with the most basic idea of fully understanding the problem and identifying what the goal is. I break tasks into smaller sub-tasks to make them more manageable and organized, then identify what tools might help solve the problem. From there, I develop and test the solution. I then troubleshoot, make adjustments, and evaluate whether the solution succeeded in achieving its goal.

## What are my ethical responsibilities to the end user and the organization?

My ethical responsibilities to the end user are to take responsibility for the quality and safety of the systems I create. That means protecting user privacy and sensitive information, developing reliable and secure software, and considering how automated decisions could affect users. There also needs to be transparency about a system's limitations, and I must follow organizational requirements and professional standards while also testing software thoroughly to reduce errors and unintended consequences. I also have a responsibility to the organization to protect its information and communicate potential risks or limitations before a system is put into use.
