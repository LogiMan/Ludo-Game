Introduction

This is a simple Ludo Game implemented in Python. The game allows 2-4 players to roll a dice, take turns, and follow Ludo rules. Players roll a dice to move their tokens, and rolling a 6 grants an extra turn. The game continues until the maximum number of dice rolls is reached.

Features

Supports 2 to 4 players

Randomized starting player selection

Players take turns rolling a 6-sided dice

If a player rolls 6, they get an extra turn

Turns automatically switch to the next player if they don’t roll a 6

Game stops after 15 rolls

How to Play

Run the script in Python.

Select the number of players (between 2 and 4).

Enter the names of all players.

The game will randomly select a starting player.

Players take turns rolling the dice.

Rolling a 6 allows a player to roll again.

The game ends after 15 rolls.

Installation

Ensure you have Python 3 installed.

Clone this repository or copy the script.

Run the script using:

python ludo_game.py

Example Gameplay Output

Let's Play Ludo!
Select number of players (2-4): 3
Enter name of player 1: Alice
Enter name of player 2: Bob
Enter name of player 3: Charlie
Player names: ['Alice', 'Bob', 'Charlie']
Charlie, start the game!
Charlie rolled a 4
Next player's turn
Bob rolled a 6
Bob rolls again!
Bob rolled a 2
Next player's turn
...
Game over after 15 rolls.

Future Improvements

Implement token movement on a board.

Add a winning condition.

Introduce safe zones and capturing mechanics.

Improve the UI/graphics with a game board.

License

This project is open-source and available under the MIT License.


