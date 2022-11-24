# Optimization_Project

The following program attempt to create the optimal basketball team of 8 players (consisting of 2 centers, 3 point and shooting guard, and 3 small and power forwards) under budget constraint using dynamic programming.

Maximize:

∑vixi

subject to

∑sixi<budget

∑xi<desired number of players

si and vi denotes salary and value\evaluation respectively of player i

xiϵ {0,1} ∀i=1,2,3...n

the data was taken from

https://www.basketball-reference.com/leagues/NBA_2022_per_game.html

https://www.nbastuffer.com/analytics101/player-impact-estimate-pie/


link to google colab: https://colab.research.google.com/drive/1xnW331Eu80-xXy5xfir-QuiDU7Cswg7m?usp=sharing

The idea behind the solution was based on the dynamic programing algorithm for solving the knapsack problem with some changes to fit our data.

intersting links to check out
knapsack problem-https://en.wikipedia.org/wiki/Knapsack_problem

Other algorithms to consider testing in the future
B&B- https://en.wikipedia.org/wiki/Branch_and_bound

![image](https://user-images.githubusercontent.com/118899152/203665225-e954bf19-9fc2-4cb7-8667-90a3b481e6b1.png)  



