CS370 – Project Two: Treasure Hunt Intelligent Agent
This repository contains my work for Project Two in CS‑370. In this project, I trained an intelligent agent (a pirate) to navigate a maze and find a treasure using deep Q‑learning. The goal wasn’t to give the agent a path, but to let it learn through trial and error. Over time, it improves by exploring the maze, getting rewards or penalties, and updating its neural network.

Project Summary
The maze environment is defined in TreasureMaze.py, and the agent interacts with that environment during training. Every move the pirate makes gives it feedback, which helps it learn what actions lead to better outcomes. The main notebook, TreasureHuntGame.ipynb, contains the training loop, Q‑learning implementation, and the results. Watching the agent go from random movement to actually finding the treasure consistently was one of the most interesting parts of the project.

Files Included
TreasureHuntGame.ipynb – My completed notebook with the full Q‑learning implementation and training results.

TreasureMaze.py – Defines the maze layout, valid actions, rewards, and game rules.

GameExperience.py – Stores experiences and prepares training batches for the neural network.

Burton_Chetra_ProjectTwo_DesignDefense.docx – My design defense explaining how the agent learns and why deep Q‑learning works for this project.

Reflection_7-3.docx – My reflection on what I learned from Project Two and how reinforcement learning became clearer through hands‑on work.

What I Learned
This project helped me understand reinforcement learning in a practical way. I learned how exploration and exploitation work together, how reward systems guide the agent, and how neural networks can approximate Q‑values. I also saw how different machine learning is from human reasoning — the agent doesn’t “see” the maze the way we do, but it still learns through repeated experience. Overall, this project made the course concepts feel more real and gave me confidence working with intelligent agents.

How to Run the Project
Install the dependencies listed in requirements.txt.

Open TreasureHuntGame.ipynb.

Run all cells to train the agent.

Watch the win rate improve as the agent learns the maze.
