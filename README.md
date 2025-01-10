# Candy-Crush-CopyCat
My first Java game! (partnered project- credit to Megan Prakash)

Welcome to our CS122 Candy Crush program!

INITIALIZATION:
Upon pressing play, the user is greeted with the menu screen.
Clicking the "INFO" button will display the rules of the game and other useful information.
There is an "exit" button at the bottom of the info and score pages that brings the user back to the menu.
Clicking the "PLAY" button initiates the game (described below).
Clicking the "SCORE" button will display a screen with the high score of wins for the current session.
While playing, you see the amount of wins completed, and if reopened, it will clear the win count to zero.

PLAYING THE GAME:
Upon clicking play a 4x6 grid of four different types of candy appears in a randomly generated pattern.
At the top left of the game screen the goal displays the number of matches the user must make to win the game.
At the top right of the game screen the score displays the number of matches the user currently has made.
To win the game the user must make enough matches to meet the goal, there is no time limit.
There is also an "exit" button if the user wishes to quit the game.
The user makes matches by selecting a candy and then selecting the candy to switch with in an adjacent spot.
Switches will not be allowed if the spot is more than one candy away, diagonal, or does not make a match.
The first switch will cause the board to check all the matches currently on the board and update the score accordingly.
Additionally, random generated candies will appear in the spaces where matches were made.
If a randomly generated candy results in a new match, the program will wait a few seconds and then make the match.
This is so that the user can see a new combo was made and the new score makes sense.

WIN SCREEN:
Once the goal is met, the user must wait for the check matches method to finish (resulting in a score potentially greater than the goal).
A win screen will be automatically displayed with the options to see score and play again.
Viewing the score displays the same result as the menu score option.
Play again results in restarting the game with the potential to add to the user's win count.


