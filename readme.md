# Tic Tac Toe Q-Learning Agent Readme

## Overview

Welcome to the Tic Tac Toe Q-Learning Agent repository! This project features an intelligent agent trained using the Q-Learning reinforcement learning algorithm to master the classic game of Tic Tac Toe. The agent is designed to learn optimal strategies through gameplay against a randomized opponent, providing a practical demonstration of Q-Learning in a controlled environment.

## Purpose

The primary goal of this project is to showcase the effectiveness of the Q-Learning algorithm in learning and optimizing game strategies within the Tic Tac Toe framework. This game's simplicity, combined with its finite state space, makes it an excellent candidate for understanding the core principles of reinforcement learning.

## How It Works

### Q-Learning Agent

- The agent learns to make decisions based on the state of the Tic Tac Toe board, optimizing its moves through trial and error.
- The learning process involves updating Q-values, which represent the expected utility of taking specific actions in given states, based on the outcomes of each game (win, lose, draw).

### Training

- The agent's training is conducted through self-play, where it adjusts its Q-values after each game, refining its strategy over time.
- The training process is customizable, allowing for the adjustment of episodes to observe variations in the agent's performance.

## Key Features

- **Flexible Training**: Control the number of training episodes to scale the learning process.
- **State Management**: The agent identifies different board configurations and determines the optimal move for each.
- **Exploration vs. Exploitation**: Implements a balance between trying new strategies (exploration) and using known successful strategies (exploitation) to improve learning efficiency.

# Two-Player Tic Tac Toe Game in the Terminal

Engage in the timeless game of Tic Tac Toe with another player directly in your terminal. This Python-based implementation offers a straightforward, interactive gameplay experience.

## How to Play

- Players alternate turns, marking either 'X' or 'O' in a 3x3 grid.
- Enter moves by specifying row and column numbers (0-based indexing), aiming to align three marks in any direction.
- The game automatically checks for a win or draw after each move, announcing the game's outcome accordingly.
- Restart the game for endless rounds of fun.

## Playing Tic Tac Toe Against a Q-Learning Agent

Challenge the computer in a strategic match of Tic Tac Toe. The computer opponent, powered by Q-Learning, adapts its moves based on learned strategies.

### How to Play:

- **Initiate the Game**: Launch the script to start, with the game board presented in the terminal.
- **Your Turn**: Play as 'X', entering moves by row and column. The computer, as 'O', follows with its trained move.
- **Progress and Outcome**: Follow the game as it unfolds to a win, loss, or draw, announced at the game's conclusion.

# 2 Player Tic Tac Toe Game with GUI

Dive into a visually engaging game of Tic Tac Toe against another player using a simple yet interactive GUI built with Tkinter.

## Features

- **User-Friendly Interface**: Enjoy a clean and straightforward GUI for game interaction.
- **Interactive Gameplay**: Two players engage in the classic game, marking 'X' and 'O' on the clickable grid.
- **Automatic Outcome Detection**: The game identifies and announces wins or draws, enhancing the play experience.
- **Instant Reset**: Easily reset the game to start anew after each round.

## How to Play

1. Launch the program to open the game window.
2. Take turns clicking on the grid to place your marks.
3. Aim to be the first to align three marks in any direction to win.
4. In case of a full grid without alignment, the game ends in a draw.
5. Use the "Reset" button for immediate game restarts.
