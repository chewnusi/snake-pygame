## Snake Game AI Implementation

This project implements an AI model to play the classic Snake game using Pygame and PyTorch.

### Files

- **game.py**: Defines the game environment and logic.
- **agent.py**: Manages the training and decision-making process for the AI agent.
- **model.py**: Implements the neural network model used by the AI agent.
- **helper.py**: Provides helper functions for visualization during training.

### Usage

To run the training process, execute `python agent.py`.

### game.py

Contains the `SnakeGameAI` class, which handles the game environment, including snake movement, food placement, and collision detection.

### agent.py

Defines the `Agent` class responsible for training the AI agent. It manages memory, training (both short and long memory), and action selection.

### model.py

Implements the `Linear_QNet` class, which defines the neural network model architecture for approximating Q-values. It also includes the `QTrainer` class for training the model.

### helper.py

Provides a function for real-time visualization of training progress using Matplotlib.

### Dependencies

- Pygame
- PyTorch
- Matplotlib