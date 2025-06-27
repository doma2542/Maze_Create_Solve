# Maze Generator and Solver

This project is a simple maze generator and solver implemented using HTML, CSS, and vanilla JavaScript. It allows users to generate a random maze and find a solution path through it.

## Project Structure

```
maze-app
├── src
│   ├── maze.js
│   ├── solver.js
│   └── style.css
├── index.html
└── README.md
```

## Files Overview

- **src/maze.js**: Contains the logic for generating the maze. It includes functions to create the maze structure, visualize it, and handle the maze generation algorithm.
  
- **src/solver.js**: Contains the logic for solving the maze. It includes functions to implement the solving algorithm, visualize the solution path, and interact with the maze generated in `maze.js`.
  
- **src/style.css**: Contains the styles for the maze visualization. It defines the appearance of the maze cells, walls, and the solution path.
  
- **index.html**: The main HTML file that integrates the JavaScript files using script tags. It sets up the structure of the webpage, including a canvas or div for displaying the maze and buttons for generating and solving the maze.

## Getting Started

To set up the project, follow these steps:

1. Create the project directory `maze-app`.
2. Inside `maze-app`, create a `src` folder.
3. Create the JavaScript files `maze.js` and `solver.js`, and the CSS file `style.css` inside the `src` folder.
4. Create the `index.html` file in the root of the `maze-app` directory.
5. Create the `README.md` file in the root of the `maze-app` directory.
6. Write the necessary code in each file to implement the maze generation and solving functionality.

## How to Run the Project

1. Open `index.html` in a web browser.
2. Use the provided buttons to generate a new maze and to solve the maze.

## Algorithms Used

- **Maze Generation**: The maze is generated using a randomized algorithm (e.g., Depth-First Search or Prim's algorithm).
  
- **Maze Solving**: The maze is solved using a pathfinding algorithm (e.g., Depth-First Search or A* algorithm).

## Contributing

Feel free to fork the repository and submit pull requests for any improvements or features you would like to add.

## License

This project is open-source and available under the MIT License.