# AI Pong with NEAT

This repository contains an AI developed using the [NEAT-Python](https://neat-python.readthedocs.io/en/latest/) library. The AI is trained to play the classic game of Pong against a human player.

## Features

- **NEAT Algorithm**: Implements NeuroEvolution of Augmenting Topologies (NEAT) to evolve neural networks for playing Pong.
- **Human Interaction**: The AI competes against a human player, adapting and improving over generations.
- **Customizable Training**: Easily adjustable NEAT configurations for experimentation.
- **Visualization**: Real-time visualization of the game and training progress.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/StiVit/Pong_AI.git
   cd Pong_AI
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have Python 3.7 or later installed.

## How to Run

1. Run the main script to start training the AI:
   ```bash
   python main.py
   ```

2. Use the arrow keys or a designated control scheme to play against the AI.

3. Observe the AI's performance improve as it learns from each game.

## NEAT Configuration

The `neat-config.txt` file contains adjustable parameters for the NEAT algorithm, including:
- **Population size**
- **Fitness function**
- **Mutation rates**
- **Crossover settings**

Modify this file to experiment with different training configurations.

## Dependencies

- Python 3.7+
- [NEAT-Python](https://neat-python.readthedocs.io/en/latest/)
- Pygame

Install all dependencies using the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

## Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [NEAT-Python Documentation](https://neat-python.readthedocs.io/en/latest/)
- Inspired by the classic Pong game.
