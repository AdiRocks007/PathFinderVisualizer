
# Pathfinding Visualizer

Welcome to the **Pathfinding Visualizer**! This interactive tool allows you to explore various pathfinding algorithms by visually observing how they navigate from a start node to an end node on a grid. This project is built using React and is designed to help users understand the mechanics behind popular pathfinding algorithms.

## 🚀 [Live Demo](https://pathfinding-visualizer-umber.vercel.app/)

## 📂 [GitHub Repository](https://github.com/AdiRocks007/PathFinderVisualizer)

## Features

- **Multiple Algorithms**: Explore a wide range of pathfinding algorithms.
- **Interactive Visualization**: Observe the step-by-step process of how each algorithm finds a path.
- **Customizable Grid**: Manually set start and end nodes, and add obstacles to see how algorithms adapt.
- **User-Friendly Interface**: Simple and intuitive controls for setting up and visualizing paths.

## 🛠️ Built With

- **React**: A powerful JavaScript library for building user interfaces.
- **CSS**: For styling and layout.
- **JavaScript**: For implementing the algorithms and interactivity.

## 🧠 Available Algorithms

- **Dijkstra's Algorithm**: A classic algorithm that guarantees finding the shortest path from the start node to the end node.
- **A***: A heuristic-based algorithm that optimizes pathfinding by considering both the cost to reach the node and the estimated cost to the end node.
- **Breadth-First Search (BFS)**: An algorithm that explores all nodes at the present depth before moving on to nodes at the next depth level, ensuring the shortest path in an unweighted grid.
- **Depth-First Search (DFS)**: An algorithm that explores as far as possible along each branch before backtracking, not guaranteed to find the shortest path.
- **Greedy Best-First Search**: An algorithm that prioritizes nodes that are closest to the end node, focusing on exploring the most promising options first.

## 🕹️ How to Use

1. **Select an Algorithm**: Choose your desired pathfinding algorithm from the dropdown menu at the top of the page.
2. **Set Start and End Nodes**: Click on any cell in the grid to set the start node (green) and the end node (red).
3. **Add Obstacles**: Click on cells in the grid to add obstacles (represented as black squares) that the algorithm must navigate around.
4. **Visualize the Path**: After setting up the grid, click the "Visualize" button to see the algorithm in action. Watch as it processes and finds the optimal path (if one exists).
5. **Reset**: Click the "Reset" button to clear the grid and start over with a fresh setup.

## 🎯 Key Concepts

- **Pathfinding**: The process of determining the shortest or most efficient path between two points.
- **Heuristics**: Strategies used by algorithms like A*** to estimate the cost of reaching the end node, allowing for faster and more efficient searches.
- **Search Space**: The grid represents a search space where algorithms explore to find the optimal path.

## 📦 Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AdiRocks007/PathFinderVisualizer.git
   cd PathFinderVisualizer
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Start the Development Server**:
   ```bash
   npm start
   ```

   Your application will open at `http://localhost:3000`.

## 🌐 Deployment

This project is deployed on Vercel and can be accessed [here](https://pathfinding-visualizer-umber.vercel.app/).

## 📚 Learn More

For more information on the algorithms used in this project, consider exploring the following resources:

- [Dijkstra's Algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
- [A*** Search Algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)
- [Breadth-First Search](https://en.wikipedia.org/wiki/Breadth-first_search)
- [Depth-First Search](https://en.wikipedia.org/wiki/Depth-first_search)
- [Greedy Best-First Search](https://en.wikipedia.org/wiki/Best-first_search)

