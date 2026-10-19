# CS-370-Current-Emerging-Trends-in-CS
CS 370 Final Project

Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

For this project, I was given starter code that created the treasure maze environment and provided much of the framework needed for the intelligent agent. This included the `TreasureMaze` and `GameExperience` classes, along with functions for creating the neural network, testing the game, and checking whether the pirate could successfully reach the treasure. My main responsibility was completing the Q-training algorithm. I created the training loop that placed the pirate at random starting locations, allowed it to choose between exploration and exploitation, stored experiences in replay memory, trained the neural network using those experiences, updated the target network, and tracked the agent's win rate. The finished program used deep Q-learning to teach the pirate how to navigate around obstacles and reach the treasure.

What do computer scientists do and why does it matter?

Computer scientists use algorithms, programming, mathematics, and logical reasoning to develop solutions to problems. This course showed me that computer science is not only about writing code that works. It also involves deciding what type of algorithm is appropriate, understanding the data being used, testing different approaches, and evaluating whether the result actually solves the original problem. In this project, the problem was pathfinding, but instead of programming a specific route for the pirate, I developed a system that could learn an effective route through experience. The same concepts can be applied to much larger problems in areas such as robotics, automation, transportation, healthcare, and engineering.

How do I approach a problem as a computer scientist?

I have learned to approach problems by first breaking them into smaller pieces and understanding what information is available, what the desired result is, and what constraints exist. With the treasure hunt project, I first needed to understand how the environment represented the maze, how actions and rewards worked, and how the provided classes interacted. From there, I could build the training process one part at a time and use the program's output and errors to determine what needed to be changed. I also learned that debugging is part of the problem-solving process rather than something separate from it. When something fails, reading the error, identifying where it occurred, and testing a focused change is usually more effective than changing several parts of the program at once.

What are my ethical responsibilities to the end user and the organization?

As a computer scientist, I have a responsibility to consider how the systems I create affect both the people using them and the organization deploying them. That includes protecting user data, avoiding unnecessary bias, making systems reliable and secure, and being transparent about their limitations. AI adds another concern because a system may make decisions that were not directly programmed by a developer. Because of that, AI systems should be tested carefully and should include human oversight when mistakes could affect safety, privacy, employment, or other important areas. Developers also have a responsibility to avoid presenting an AI system as more reliable or capable than it actually is and to consider potential unintended uses before the technology is deployed.
