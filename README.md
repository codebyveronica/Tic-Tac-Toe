# Tic-Tac-Toe with React

## Overview

This project implements the classic **Tic-Tac-Toe** game using React. It is designed as a learning experience for developers who want to understand and practice React's core concepts, including components, props, state management, and advanced techniques.

## Features

- **React Fundamentals**:

  - Learn how to build and structure components.
  - Understand the usage of `props` and `state` in a React application.

- **Gameplay**:

  - Interactive Tic-Tac-Toe game with a turn-based system.
  - Winning logic to determine the winner or a draw.

- **Time Travel**:
  - Navigate through the game history using a "time travel" feature.
  - Learn about React's strengths, such as immutability and state management.

## Project Structure

The code is split into three main components:

1. **Square**: Represents an individual cell in the Tic-Tac-Toe board.
2. **Board**: Handles the layout of the game board and tracks gameplay logic.
3. **Game**: Manages the game state, history, and time travel functionality.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-react.git
2. Navigate to the project directory:
   ```bash
   cd tic-tac-toe-react
3. Install the dependencies:
   ```bash
   npm install
4. Start the development server
   ```bash
   npm start
5. Open the game in your browser at http://localhost:3000.

## Key Concepts Demonstrated

- **Component Composition**: Breaking the application into reusable components (`Square`, `Board`, `Game`).
- **State Management**: Using `useState` to handle game state and history.
- **Props**: Passing data and event handlers between components.
- **Immutability**: Maintaining the integrity of the game history for the time travel feature.

## Code Highlights

- The game logic is implemented in the `calculateWinner` function, which determines the winner or if the game ends in a draw.
- The `jumpTo` function allows navigation between moves, showcasing React's ability to handle state changes dynamically.
  Demo

## Learning Outcomes

By working on this project, you will:

- Gain a solid understanding of React's core principles.
- Learn how to build interactive UIs efficiently.
- Understand the importance of immutability and its role in managing application state.

Feel free to fork, modify, and experiment with the project to enhance your React skills!

## My Learning

This project is a tutorial made by react.dev to show the basics of React. I found it a great way to learn, and at the same time practice, to fix the concepts in an interactive, very well created and explanatory way. It's a great way for anyone to learn, especially for those who like to learn by doing!

## Author

[codebyveronica](https://github.com/codebyveronica?tab=repositories)

## License
This project is open source and available under the MIT License.
