# NUMBER_GUESSING_GAME_JAVA

**Number Guessing Game**

This Java program implements a simple number guessing game. Here's how it works:

1. **Setup:**
   - The game generates a random number within a specified range (default: 1 to 100).
   - Players have a limited number of attempts to guess the correct number (default: 10 attempts per round).
   - The game consists of a total of 3 rounds.

2. **Playing a Round:**
   - In each round, players are prompted to guess a number within the given range.
   - Feedback is provided on whether the actual number is greater or smaller than the guess.
   - Players aim to guess the number within the given attempts for each round.

3. **Scoring:**
   - Points are earned based on the number of attempts left after guessing the correct number.
   - The score for each round is calculated as `MAX_ATTEMPTS - attempts_taken`.

4. **Total Score:**
   - The total score is the sum of scores from all rounds played.

5. **Game Over:**
   - After completing the specified number of rounds, the game ends, and the total score is displayed.

6. **Customization:**
   - Players can customize the game by adjusting the following constants in the `Task2` class:
     - `MIN_RANGE`: Minimum value for random number generation.
     - `MAX_RANGE`: Maximum value for random number generation.
     - `MAX_ATTEMPTS`: Maximum attempts allowed to guess the number in each round.
     - `MAX_ROUNDS`: Total number of rounds in the game.

7. **Running the Program:**
   - Compile the Java file (`NumberGuessingGame.java`).
   - Run the compiled Java program.

8. **Contributing:**
   - Feel free to contribute to this project by creating issues, suggesting improvements, or submitting pull requests. Your contributions are welcomed and appreciated!
