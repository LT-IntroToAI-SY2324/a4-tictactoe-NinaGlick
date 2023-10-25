# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
 the hardest part was figuing out the most effcieint way to check if a player had won. Instead of trying each possible winning sequence, I used a for loop to determine if a row or column had three in a row. Then I just wtote a conditional statement to see if somone one wit threee in a row diagonally. 

2. Explain how you would add a computer player to the game.
instead of having a second player, the computer would take the place of the other player and make moves on its own. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
the computer would look to see the most advantageous place to place its letter. it could do this by checking the surrounding spaces for the opponents letter, and its own letter. for example, if the player is x and the computer is o, the computer will look if there is a place where there may be 2 x's and block the person from winning, or it may look for places where there are already 2 o's and place it there.