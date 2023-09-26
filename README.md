# Poker_Card_game
## Introduction
Welcome to the Poker Card Game repository.
This program simulates the classic card game of Poker, allowing users to draw, keep, or replace cards to form the best hand possible.

## How to Play
Start the Game: Upon starting the game, the user is dealt an initial hand of five cards.

Final Hand: After making decisions on each card, the user receives the final hand.

Hand Evaluation: The program then evaluates and displays the value of the hand to the user.

## Compilation
To compile the poker game:

Navigate to the project directory in your terminal.

Run the command: make

This will generate an executable named poker.

### Running the Game
After successful compilation, you can run the game with the following command:
./poker
### Cleaning up
If you want to clean up the compiled files (e.g., before pushing to a version control system), you can use the following command:
make clean
This will remove the generated poker executable and any object files.

## The Code Structure
getFirstHand(): Deals the first five cards to the user.

getFinalHand(): Looks through each of the five cards in the first hand and asks the user if they want to keep the card. If they say no, they get a replacement card.

getSuit(): Transforms the suit integer value to a character representing the suit.

getRank(): Transforms the rank integer value to a character representing the rank.

analyzeHand(): Reviews the final hand and determines the value of the hand.

### Installation and Usage
Clone this repository to your local machine.

Navigate to the project directory in your terminal.

Compile the source code using a C compiler.

Run the compiled program.

### Dependencies
Standard C libraries.

A C compiler, e.g., GCC or Clang.

#### Contribution
If you would like to contribute to this project or spot any bugs, please submit a pull request or open an issue. Feedback and suggestions are welcome.

