This Hangman game, created using Python and the Pygame library, is an upgraded and interactive version of the traditional paper-and-pencil game. It successfully combines programming logic, graphical design, and user interaction into one complete project.

Interactive and Visual Design

The game replaces plain text with colorful graphics, clickable letter buttons, and a step-by-step animated hangman figure.

Hints are provided for each word, improving user engagement and making the game accessible to beginners.

Smooth Game Flow

A main game loop ensures continuous updates to the screen while checking for user input events such as mouse clicks and key presses.

Collision detection is implemented to identify when the player clicks on a specific letter button.

Logical Gameplay Mechanics

Correct guesses reveal the letter positions in the word.

Incorrect guesses increase the hangman_status counter, which visually adds new parts to the hangman drawing.

The game ends with a win when the player reveals the whole word or a loss after six wrong guesses.

User-Friendly Restart Options

After each round, players can press SPACE to start a new game or ESC to quit.

This quick restart system makes the game easy to replay.

Educational Value

Demonstrates randomization for selecting words from a list.

Teaches event-driven programming through mouse and keyboard handling.

Uses loops, conditionals, and lists for game logic.

Shows how to draw shapes, text, and handle colors in Pygame.

Scoring System

Rewards correct guesses with a score increment.

Displays the total score and the number of wrong attempts, giving players performance feedback.


