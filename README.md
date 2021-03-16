Implementation of the Minimax algorithm for adversarial search following the pseudocode in Figure 5.3 in the textbook "Artificial Intelligence: A Modern Approach" Third Edition by Stuart J. Russell and Peter Norvig. Afterwards, Minimax implementation was extended to use alpha-beta pruning, in order to speed up the search. Pseudocode for alpha-beta pruning is provided in Figure 5.7 in the textbook.

For this implementation, the “Pac-Man projects” codebase developed at UC Berkeley was followed. The Pac-Man projects were developed for UC Berkeley’s introductory course in Artificial Intelligence, and later made available for other universities to use (see http://ai.berkeley.edu/project_overview.html for an overview of these projects). The projects cover a variety of Artificial Intelligence techniques, exploring them through the world of Pac-Man. This Python codebase implements the rules of Pac-Man and visualizes the game. 

To run these project code, the program "autograde.py" that will run the various tests on Minimax and Alpha-beta implementations in order to verify the correct implementation of all the subtleties of these algorithms is included.


###Provisional grades

-----------------
Question q1: 4/4

Question q2: 5/5

Question q3: 5/5

Question q4: 5/5

Question q5: 6/6

-----------------


#### Q1: Reflex Agent

Implementation of a very basic function that just goes for the closest food and avoids the ghost if it is very close.


#### Q2: Minimax / Q3: Alpha-Beta Pruning / Q4: Expectimax

These algorithms are also implemented as robust as possible.


#### Q5: Evaluation Function

Similar to Q1 but includes the addition of a few multipliers to a few variables for the final score according to their significance.

****Check the code comments for full explaination****
