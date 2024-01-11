# Monty Hall Simulation

## Overview
This Jupyter Notebook contains a simulation of the Monty Hall problem, a probability puzzle based on a game show scenario. The simulation is written in Python and uses randomization to model the player's choices and outcomes.

## Files
- `Monty_Hall_Simulation.ipynb`: Jupyter Notebook containing the simulation code.
- `README.md`: This file providing an overview of the simulation.

## Monty Hall Problem
The Monty Hall problem is a probability puzzle named after the host of the television game show "Let's Make a Deal," Monty Hall. The problem can be summarized as follows:
1. A contestant picks one of three doors, behind one of which is a car (the prize), and behind the other two are goats.
2. After the contestant makes their initial choice, the host, who knows what is behind each door, opens one of the other two doors to reveal a goat.
3. The contestant is then given the option to stick with their original choice or switch to the remaining unopened door.
4. The door the contestant chooses is opened, and they win whatever is behind it.

## Simulation Details
- The simulation runs a specified number of games (controlled by the variable `num_games`).
- Two scenarios are considered: always switching doors and never switching doors.
- The simulation calculates the winning percentage for each scenario.

## Results
After running the simulation, the winning percentage for both scenarios is displayed.

## How to Run
Simply execute the code cells in this notebook to run the simulation.

Feel free to modify the `num_games` variable or other parameters to explore the behavior of the Monty Hall problem further.

---

**Note:** The code in this notebook includes print statements to display the outcomes of a few initial games for illustration purposes. These can be removed or modified as needed.
