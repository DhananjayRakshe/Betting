Slot Machine Game - User Manual
Welcome to the Slot Machine Game! This is a simple JavaScript-based gambling game designed to provide a fun learning experience for new developers. Below is a step-by-step guide on how to play and use the game.

How to Play:
Objective
The goal of the game is to win money by betting on rows of symbols. Matching symbols on a row will multiply your bet by a set value, depending on the symbol.
Game Steps:
1. Deposit Money: Enter an initial deposit amount to start playing.
2. Choose Lines: Choose how many lines (1-3) you want to bet on.
3. Place Your Bet: Enter the bet amount for each line. The total bet amount is the bet per line multiplied by the number of lines.
4. Spin the Slot Machine: The game generates a random set of symbols across rows.
5. Check Winnings: If the rows match symbols according to the rules, you win based on the symbol values.
6. Repeat or Exit: You can choose to play again if you have money remaining or exit the game.

Symbol Values:
  A: 5,
  B: 4,
  C: 3,
  D: 2,

Inputs and Prompts:
1. Deposit
Prompt: "Enter a deposit amount:"
Input a positive number representing the initial money.

2. Number of Lines
Prompt: "Enter the number of lines to bet on (1-3):"
Input a number between 1 and 3.

3. Bet Amount
Prompt: "Enter the bet per line:"
Input a positive number not exceeding your available balance divided by the number of lines.

4. Play Again
Prompt: "Do you want to play again (y/n)?"
Input "y" to play again or any other key to quit.

Gameplay Rules:
The game uses a 3x3 slot machine (3 rows and 3 columns).
Each spin randomly selects symbols for the slot.
You win money if all symbols in a row match, based on the following formula:
Winnings = Bet Amount × Symbol Multiplier
The winnings are added to your balance if you win. If you lose all your money, the game ends.

Example:
Deposit Money: You enter 100.
Choose Lines: You bet on 2 lines.
Place Your Bet: You enter 10 for the bet per line.
Spin: Symbols are randomly selected.
Check Winnings: If you win, the winnings are added to your balance.
Play Again: You can continue playing or quit.
