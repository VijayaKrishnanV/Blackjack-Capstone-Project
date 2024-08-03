# Blackjack-Capstone-Project
This Python script simulates a Blackjack game where a player competes against the computer by drawing cards and aiming to get a hand value closest to 21 without exceeding it, following the classic Blackjack rules.

## How to Play

1. The game starts by dealing two cards to both the user and the computer.
2. The user can choose to draw another card or pass.
3. The computer will continue to draw cards until its hand value is 17 or higher.
4. The goal is to have a hand value closest to 21 without exceeding it.

## Rules

1. The deck is unlimited in size.
2. There are no jokers.
3. The Jack, Queen, and King all count as 10.
4. The Ace can count as 11 or 1.
5. The cards in the deck have equal probability of being drawn.
6. Cards are not removed from the deck as they are drawn.

## Functions

- `deal_card()`: Returns a random card from the deck.
- `calculate_score(cards)`: Takes a list of cards and returns the score. It handles Blackjack and adjusts the Ace value if needed.
- `compare(user_score, computer_score)`: Compares the user and computer scores to determine the game outcome.
- `clear_screen()`: Clears the console screen for better readability during the game.
- `play_game()`: Manages the game flow, dealing cards, and handling user and computer actions.

## How to Run

1. Ensure you have Python installed on your system.
2. Save the script to a file named `blackjack.py`.
3. Run the script using the command `python blackjack.py`.
4. Follow the on-screen prompts to play the game.

