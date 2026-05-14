# Tic-Tac-Toe Neural Network

A browser-based implementation of a self-learning AI opponent, developed using the **Brain.js** library to explore the foundations of supervised learning and iterative data aggregation.

## Project Overview

This project features a neural network trained to play Tic-Tac-Toe against a human opponent. Rather than relying on static "if-else" logic or a standard minimax algorithm, this agent utilises a weighted neural network to predict the most effective moves based on historical gameplay patterns.

The model was initially seeded with a foundational dataset and continues to refine its decision-making heuristics by aggregating data from every game played, allowing the AI to adapt to various human strategies over time.

## Key Features

*   **Dynamic Learning Pipeline:** The AI records and processes game-state arrays into weighted inputs, ensuring the model adapts to new defensive and offensive patterns.
*   **Tiered Difficulty Logic:** The single-player mode features three distinct difficulty settings, which correspond to the **volume of training iterations** and the **computational depth** the model processes:
    *   **Novice:** Exploratory play with minimal training data.
    *   **Intermediate:** Balanced strategy with moderate pattern recognition.
    *   **Expert:** Highly optimised defence and offensive prioritisation based on extensive training.
*   **Modern Web Interface:** A clean, responsive UI built with HTML5 and CSS3, demonstrating the seamless integration of machine learning models into lightweight, client-side environments.

## Technical Stack

*   **Logic:** JavaScript (ES6+)
*   **Neural Network Library:** Brain.js
*   **Data Structure:** JSON-based training datasets
*   **UI/UX:** HTML5, CSS3

## Architecture & Implementation

This repository showcases the fundamental structure required to build an AI agent from the ground up:
1.  **Input Normalisation:** Converting the 3x3 game board into a numerical format the neural network can process.
2.  **Iterative Training:** A mechanism that saves new game data to enhance the model's accuracy after each match.
3.  **Prediction Logic:** Utilising weighted outputs to determine the highest-probability winning move in real-time.

---

## Getting Started

To run the project locally:
1. Clone the repository.
2. Open `index.html` in any modern web browser.
3. Select the player mode and then your difficulty level and begin the training session!

## Interface Preview

![](https://github.com/msizimkhize/Tic-Tac-Toe-ML-Training-Version-I/blob/main/gameplayshots.png?raw=true)
---

#### Reach Out on LinkedIn

[![](https://raw.githubusercontent.com/msizimkhize/Vegetable-Prices-2022-MySQL-PowerBI/adc81f1d2ee7e3d74868bc8fdf859f13eba1fe5b/IMG/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c696e6b6564496e2d436f6e6e6563742d626c75653f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e6b6564696e.svg)](https://www.linkedin.com/in/msizimkhize/)
