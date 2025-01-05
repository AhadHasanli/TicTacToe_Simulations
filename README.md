Tic-Tac-Toe Strategy Simulations Report


1. Introduction
This report presents the results of simulating various strategies for the game of Tic-Tac-Toe. The
strategies implemented include Random, Minimax, and Alpha-beta Pruning. The goal is to
compare their performance in terms of wins and execution time when playing against a Random
opponent. Simulations are run for both players 'X' and 'O'.


2. Methodology
The implementation of the game follows standard Tic-Tac-Toe rules. Three strategies are
evaluated:
 Random Player: Makes moves at random.
 Minimax Player: Uses the Minimax algorithm to make optimal decisions.
 Alpha-beta Player: Utilizes Alpha-beta pruning to optimize the Minimax algorithm.
Each strategy was simulated 100 times against a Random player, alternating between playing as
'X' and 'O'. Execution time and the number of wins were recorded.


3. Results
The results of the simulations, including the number of wins and execution time for each
strategy, are presented below. These results demonstrate the effectiveness of Minimax and
Alpha-beta pruning compared to the Random strategy.
Simulation Results
 Random Player, 'X': Wins - 57, Time - 0.601 seconds
 Random Player, 'O': Wins - 49, Time - 0.530 seconds
 Minimax Player, 'X': Wins - 65, Time - 1.347 seconds
 Minimax Player, 'O': Wins - 72, Time - 1.805 seconds
 Alpha-beta Player, 'X': Wins - 80, Time - 1.022 seconds
 Alpha-beta Player, 'O': Wins - 75, Time - 1.014 seconds


4. Analysis
The results clearly indicate that both Minimax and Alpha-beta Pruning outperform the Random
strategy in terms of win rates. Alpha-beta Pruning achieves similar win rates to Minimax but
requires less execution time, demonstrating its efficiency in optimizing game tree search.


5. Conclusion
This project successfully demonstrated the implementation and performance of various Tic-Tac-
Toe strategies. The simulations highlight the advantages of using advanced strategies like
Minimax and Alpha-beta Pruning over a Random strategy. Future work could involve further
optimizing these algorithms or applying them to more complex games.
