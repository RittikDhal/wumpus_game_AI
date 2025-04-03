# wumpus_game_AI
A basic wumpus AI agent
Wumpus World AI Simulation
This project is a Wumpus World AI Simulation using Pygame and BFS-based pathfinding. The AI agent navigates a 10x10 grid-based environment, avoiding dangers like Wumpus and pits while searching for gold. The simulation generates a GIF animation of the agent's journey.

Features
Randomized Environment: The game places the Wumpus, gold, and pits randomly.

Sensory Indicators: Cells near pits have breeze, and cells near the Wumpus have stench.

AI Pathfinding: Uses Breadth-First Search (BFS) to find the safest path to the gold while avoiding hazards.

Graphical Simulation: The environment and agent movement are rendered using Pygame.

GIF Generation: Captures the agent's path and saves it as a GIF for visualization.

Dependencies
pygame (for rendering the game)

imageio (for GIF generation)

ipywidgets (for interactive display in Jupyter Notebooks)

How It Works
The grid is initialized with randomly placed gold, Wumpus, and pits.

The AI senses the environment using indicators (glitter, stench, breeze).

BFS Pathfinding Algorithm finds the shortest and safest route to the gold.

The agent moves step by step, avoiding dangerous areas.

A GIF of the movement is generated and displayed.

Running the Code
Simply execute the script in a Jupyter Notebook or a Python environment supporting Pygame. The simulation will run and display the AI's decision-making process.

Future Enhancements
Implement A search* for more efficient pathfinding.

Add multiple Wumpus for increased complexity.

Allow user-defined grid size and obstacle density.

This project is a great way to understand AI decision-making in a game-like environment!
