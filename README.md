## AI-Projects

#  1- Iris Flower Species Classification

 * Implemented Perceptron Learning Rule and Gradient Descent Delta Rule from
scratch to classify Iris flower species, using an 80/20 train
test split for evaluation. Compared model accuracy across different activation functions and learning rates, analyzing how each algorithm
 performs and adapts to the dataset.

 * Experimented with hyperparameter tuning to minimize loss and improve prediction accuracy, documenting results and insights for both
 models.

#  2- Customer Segmentation Using K-Mean and K-Medoids

##  K-Means Clustering
* Implemented K-Means Clustering from scratch on customer demographic data using NumPy and pandas, applying clustering for different values
  of K (2, 3, 4) based on Age, Annual Income, and Spending Score.
* Visualized clusters with Matplotlib and interpreted customer segments to suggest data-driven marketing strategies.

## K-Medoids Clustering
* Developed a custom K-Medoids Clustering algorithm on the same dataset, clustering customers with various K values (2, 3, 4) to analyze
  medoid-based groupings.
* Used visualizations to interpret clusters and proposed actionable marketing insights based on identified customer segments.

#  3- Allocation System using K-Means Clustering
 *  Developed an automated exam management system using K-Means Clustering to group 2400+ students by batch and domain across 30
 rooms, ensuring optimal seating plans under room capacity constraints.

 *  Implemented faculty allocation logic based on domain expertise, and created a user-friendly interface to manage inputs and generate real
time reports for seating and invigilation assignments

#  4-Eight Puzzle Solver using A_Star

* The code creates a GUI-based Eight Puzzle game using Tkinter, where the puzzle starts with a solved state and can be scrambled for play.

* It includes a solve() function meant to solve the puzzle using the A* Search algorithm, though the solving logic is expected to be implemented
  in the external EightPuzzle class.

#  5- Hill cilmbing algos and Alpha Beta Algo Problem Solve

## Hill cilmbing algos
* Solved the 8-Queen problem using Hill Climbing with Stochastic Search, where multiple random moves are explored to escape local optima and find a conflict-free board configuration.

* Implemented Simulated Annealing for the 8-Queen problem, allowing occasional worse moves based on probability to avoid getting stuck in local minima, leading to an effective global search.

## Alpha Beta Algo

 * Solved the Tic-Tac-Toe game using the Minimax algorithm, ensuring optimal moves by recursively evaluating all possible game outcomes to choose the best strategy.

* Enhanced the solution with Alpha-Beta Pruning, optimizing the Minimax search by eliminating unnecessary branches, making the AI more efficient without compromising decision quality.

#  6- Sudoku Puzzle Solver using CSP Formulation
* CSP-Based Backtracking Algorithm: Modeled Sudoku as a Constraint Satisfaction Problem (CSP) by enforcing row, column, and block constraints during number placement. Solver dynamically identifies empty cells as variables and iterates through possible values while preserving constraints, a classic CSP-solving approach.

* Interactive GUI: Developed an intuitive interface using Tkinter to let users select difficulty and puzzles interactively, with visual feedback displaying both the initial and solved board states.

