# Traveling Salesman Problem Solver with Genetic Algorithm

The traveling salesman problem (TSP) consists of finding the minimum route to connect N cities, which are all visited only once and which returns to its departure city. This classic optimization problem is very simple to state but very difficult to solve. Indeed, the most naive algorithm consisting of comparing all possible paths requires a calculation time which is proportional to N!. Slightly more efficient exact algorithms have been created, but they do not allow us to go much further than 200,000 cities.

## Overview

This solution provides a desktop application built in Python using Tkinter and a genetic algorithm to solve the TSP.

### Files

- `tsp_problem_algorithm_genitic.py`: Main Python script implementing the TSP solver with Tkinter GUI and genetic algorithm.
- `images/`: Directory containing icons used in the GUI.
- `logo.ico`: Icon file used for the application.

## Features

- **Interactive Graph**: Users can draw nodes on the canvas by clicking, representing cities for the TSP.
- **Conversion to Distance Matrix**: Converts the drawn graph into a distance matrix by specifying distances between nodes.
- **TSP Solving**: Solves the TSP using a genetic algorithm and displays the best route found.
- **Dark/Light Mode**: Supports both dark and light modes for user preference.
- **Graph Clearing**: Option to clear the graph and start fresh.

## Installation

To run the application, follow these steps:

1. Clone the repository or download the source files.
2. Ensure you have Python installed on your system.
3. Install the required libraries by running:
    ```
    pip install numpy deap customtkinter
    ```
4. Convert the Python script to an executable file using PyInstaller:
    ```
    pyinstaller --onefile -w --icon="images/logo.ico" "tsp_problem_algorithm_genitic.py"
    ```
5. Run the generated executable file.

## Usage

1. Launch the application.
2. Draw nodes on the canvas by clicking to represent cities.
3. Connect nodes and convert to a distance matrix.
4. Solve the TSP using the genetic algorithm.
5. View the best route found and its fitness score.
6. Optionally, switch between dark and light mode.
7. Clear the graph to start fresh.

## Contributors

- [OUARAS Khelil Rafik](https://github.com/OUARAS-khelil-Rafik)
