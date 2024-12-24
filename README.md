# Chess-Bot

This repository contains a Python-based Chess Bot built using the **python-chess** library. The bot is designed to play chess autonomously and incorporates several advanced features and strategies to ensure a challenging experience for users.

## Project Overview
The Chess Bot leverages the **Minimax algorithm** with **Alpha-Beta Pruning** for efficient decision-making during gameplay. It evaluates board positions using a combination of multiple evaluation functions, allowing it to balance strategic and tactical considerations.

### Key Features
- **Move Validation:** Ensures only legal moves are made during the game.
- **Customizable Gameplay:** Supports bot vs. bot modes.
- **Minimax Algorithm:** Implements depth-limited Minimax for decision-making.
- **Alpha-Beta Pruning:** Optimizes Minimax by pruning unpromising branches, reducing computation time.
- **Evaluation Functions:** Uses a mixture of evaluation strategies, including:
  - Material advantage.
  - Piece positioning and mobility.
  - King safety.
  - Control of the center.

## Repository Contents
- `Chess_Bot.ipynb`: Jupyter Notebook containing the Chess Bot implementation.

## Prerequisites
### General Requirements:
- Python 3.7 or later
- Jupyter Notebook

### Python Libraries:
- `python-chess`
- `numpy`

You can install the required libraries using pip:
```bash
pip install python-chess numpy
```

## Getting Started
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/chess-bot.git
   cd chess-bot
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open and run the `Chess_Bot.ipynb` notebook.

4. Follow the instructions within the notebook to:
   - Play against the bot.
   - Watch bot vs. bot games.
   - Analyze the bot's decision-making process.

## Usage Instructions
- Start the game by specifying whether you want to play as white or black.
- Use standard algebraic notation for making moves (e.g., `e2e4`).
- View the board after each move and monitor the bot's decisions.

## Future Improvements
- Integrate a GUI for enhanced user interaction.
- Train and integrate a neural network for improved board evaluation.
- Add support for time controls and chess clocks.
- Incorporate opening book strategies for faster and stronger early-game play.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

Enjoy playing and experimenting with the Chess Bot! ♟️

