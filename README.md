# SLOT-MACHINE-by-Tech-with-Tim
This project is a Python-based slot machine game that simulates a simple gambling experience. The base code was sourced from a tutorial by Tech With Tim on YouTube, which served as a learning tool for programming in Python. The original code can be found in the GitHub repository: [Python-Slot-Machine](https://github.com/techwithtim/Python-Slot-Machine). This project has been enhanced with additional features and improvements.

## Features

- **Slot Machine Simulation**: The game simulates a slot machine with 3 rows and 3 columns, allowing players to bet on up to 3 lines.
- **Balance Management**: Players start with an initial balance, can deposit more money, and place bets on the slot machine.
- **Winning Condition**: Players win if any of the lines they bet on matches a winning combination.
- **Game Termination and Deposit Options**: The game offers the option to either quit or deposit more money if the player's balance runs out, ensuring continuous gameplay.
- **Game Interface**: The game uses a simple text-based interface to interact with the player.

## Improvements Over the Original Code

This project builds on the base code provided in the Tech With Tim tutorial, with the following enhancements:

1. **Game Continuation on Zero Balance**: The game prompts the player to either quit or deposit more money if their balance reaches zero, ensuring that the player isn't forced to quit immediately.

2. **Enhanced Win Condition**: The original game required exact matches across all bet lines to win. This project modifies the win condition so that a player wins if any of the lines they bet on matches a winning combination. This makes the game more fair and engaging.

3. **Improved User Input Validation**: The game now includes improved validation for user inputs, ensuring that only valid numbers are entered for bets, deposits, and line selection.

## Installation

1. Clone this repository to your local machine using:
    ```bash
    git clone https://github.com/yourusername/Slot-Machine-Gambling-Game.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Slot-Machine-Gambling-Game
    ```
3. Ensure you have Python installed on your machine (Python 3.6+ is recommended).

4. Run the game:
    ```bash
    python slot_machine.py
    ```

## How to Play

1. **Deposit Money**: The game starts by asking how much money you would like to deposit into your balance.
2. **Select Lines to Bet On**: Choose the number of lines (1 to 3) you wish to bet on.
3. **Place Your Bet**: Set the amount you want to bet on each line. The total bet is calculated as `number of lines × bet per line`.
4. **Spin the Slot Machine**: The slot machine will spin and display the outcome. If any of the lines you bet on match, you win a reward based on your bet.
5. **Balance Management**: If you win, your winnings are added to your balance. If you lose, your bet is subtracted from your balance.
6. **Continue or Quit**: The game continues until you choose to quit or your balance reaches zero. If your balance is zero, you can choose to deposit more money or quit.

## Possible Improvements

While this project includes several enhancements over the original tutorial code, there are still areas that could be further improved:

1. **Graphical User Interface (GUI)**: Integrate a GUI using Tkinter or Pygame to make the game more visually appealing.
   
2. **Sound Effects**: Add sound effects to enhance the gaming experience, such as sounds for winning, losing, and spinning the slot machine.

3. **Multiple Slot Machines**: Allow the player to choose from different slot machines with varying levels of risk and reward.

4. **Save/Load Game State**: Implement a feature to save the game state and allow players to resume their game later.

5. **Statistics and Leaderboards**: Track player statistics such as total games played, total wins, and create a leaderboard to compare results.

6. **More Complex Win Conditions**: Add more advanced win conditions, such as diagonal matches or wildcard symbols, to increase the complexity and excitement of the game.

## Acknowledgments

This project was inspired by the [Tech With Tim Python Slot Machine Tutorial](https://www.youtube.com/watch?v=th4OBktqK1I&list=WL&index=46&t=132s). Special thanks to Tech With Tim for the original code and educational content.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by submitting issues, suggesting new features, or making pull requests!
