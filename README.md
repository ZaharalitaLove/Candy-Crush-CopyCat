# Candy-Crush-CopyCat
My first Java game! (partnered project- credit to Megan Prakash)

This project is a simple Java-based clone of the popular Candy Crush game, developed using Java Swing for the graphical user interface. The game allows players to match candies on a 4x6 grid and aims to reach a specific match goal to win.
Features
* Menu Screen:
    * INFO button displays game rules and instructions.
    * SCORE button shows the high score for the current session.
    * EXIT button to quit the game or go back to the main menu.
* Game Screen:
    * A 4x6 grid of randomly generated candies.
    * Goal number of matches and current score are displayed at the top.
    * Exit button to quit the game at any time.
* Gameplay:
    * Players make matches by swapping adjacent candies.
    * Matches are automatically detected and the score is updated.
    * New candies are generated to fill empty spaces after each match.
    * Matches may trigger new combos as random candies are generated.
* Winning the Game:
    * The player wins once the goal number of matches is reached.
    * A win screen is displayed with options to view the score or play again.
    * The win count is reset to zero when reopening the game.
      
Game Rules
* A match is formed when 3 or more candies of the same type are lined up vertically or horizontally.
* Only adjacent candies can be swapped (no diagonal moves).
* After each match, new candies will be randomly generated to replace the matched ones.
* If a new match is created by the random candies, it will be detected after a brief delay.

Skills Demonstrated
* Java Swing GUI: Building a user-friendly interface for the game.
* Game Logic: Implementing match-checking, score tracking, and win conditions.
* Randomization: Generating random candies to simulate gameplay dynamics.
* Event Handling: Managing user input for candy selection and swapping.



