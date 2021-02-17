# Pipopipette
The game Dot for 2 human players in Java (the programming language)
Created without using graphics (IHM)
                                                                                                01234 (rows and columns are numbered so you can choose your move easily) 
Tableau.java: create the interface of the game and calculate the number of possible moves (ex: 0* * *  = tableau 2x3, possible move = 7). Size max = 5x6
                                                                                               1
                                                                                               2* * *
                                                                                               
Move.java : here's how it works. Game starts with player 1 choosing a move
-> if the move is valid, the move will be made on the table (either a '-' if the row is even, a '|' if the row is odd), replacing the space. Then change turn to player 2
-> invalid -> choose again
      When a player fill the square (not really a square but yeah), he/she gains a point and continue to play. The game will announce the score of both player each time someone gains a point. 
      And lastly, announce the winner !
