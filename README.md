# Dice Game

A simple dice game where players take turns to roll a dice and hold their scores. The first player to reach 100 points wins the game.

## How to Play

1. **Roll the Dice:** 
   - Click the "Roll Dice" button to roll the dice.
   - The dice will show a number between 1 and 6.
   - If the dice shows any number other than 1, it will be added to the current player's score.
   - If the dice shows 1, the current player's turn ends, and the next player's turn begins.

2. **Hold the Score:**
   - Click the "Hold" button to add the current score to the total score of the active player.
   - The turn then switches to the next player.

3. **Winning the Game:**
   - The first player to reach a total score of 100 points wins the game.
   - The winning player will be highlighted.

4. **New Game:**
   - Click the "New Game" button to reset all scores and start a new game.

## Game Controls

- **Roll Dice:** Click to roll the dice and add the result to the current score unless it is 1.
- **Hold:** Click to add the current score to the total score and pass the turn to the next player.
- **New Game:** Click to reset the game and start over.

## Code Overview

- **HTML:** Structure of the game interface.
- **CSS:** Styling for the game elements.
- **JavaScript:** Game logic including rolling dice, holding scores, switching players, and determining the winner.

## JavaScript Functions

- **init:** Initializes the game by setting scores to zero and hiding the dice.
- **switchPlayer:** Switches the active player and resets the current score.
- **Roll Dice Event Listener:** Rolls the dice and updates the current score or switches the player if 1 is rolled.
- **Hold Event Listener:** Adds the current score to the total score, checks for a winner, and switches the player.
- **New Game Event Listener:** Resets the game by calling `init`.

Enjoy playing the Dice Game!

