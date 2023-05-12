# Number Guessing Game in Python

This is a simple number guessing game implemented in Python. The game allows the user to guess a randomly generated number within a specified range.

## How to Play

1. Run the Python script.
2. Enter the lower bound and upper bound of the range when prompted.
3. The script will generate a random number within the specified range and store it for reference.
4. You will be prompted to enter your guess.
5. If your guess is greater than the generated number, you will receive the message: "Try Again! You guessed too high."
6. If your guess is smaller than the generated number, you will receive the message: "Try Again! You guessed too small."
7. Keep guessing until you correctly guess the number.
8. If you guess the number in the minimum number of attempts, you will receive the message: "Congratulations!"
9. If you are unable to guess the number within the minimum number of attempts, you will receive the message: "Better Luck Next Time!"

## Implementation Details

The game is implemented using a `while` loop to allow repetitive guessing. The random number is generated using the `random` module in Python. The lower and upper bounds provided by the user are used to define the range of possible numbers.

Feel free to modify the `max_guesses` variable to change the number of allowed guesses according to your preference. Have fun playing the number guessing game!