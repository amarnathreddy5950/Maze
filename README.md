# Maze Solver Project

This project contains a maze-solving algorithm using search strategies like depth-first search (DFS) and breadth-first search (BFS). The program reads a maze from a text file and attempts to solve it, displaying the solution both in the console and as an image.

## Project Overview

The maze solver reads a maze from a text file, where walls, start, and goal positions are defined. Using search algorithms, it finds the path from the start to the goal and outputs the result.

The start position is marked by 'A', the goal position is marked by 'B', and walls are represented by any character other than spaces.

## Project Structure

src0/
    maze.py                 - Main maze-solving program
    maze1.txt               - Sample maze file 1
    maze2.txt               - Sample maze file 2
    maze3.txt               - Sample maze file 3
    maze.png                - Output image file showing the solved maze
requirements.txt            - Required Python dependencies

## Setup

1. Clone the repository:
   git clone https://github.com/yourusername/maze-solver.git
   cd maze-solver/src0

2. Install dependencies:
   Ensure you have Python 3 installed, then install the required dependencies:
   pip install -r requirements.txt

## Usage

To solve a maze:
   python maze.py maze1.txt

This will print the maze, solve it, and save an image of the solution as maze.png.

## Example Input:
A        B
█████ ███
     █   
████ ████

In this example:
- 'A' is the start.
- 'B' is the goal.
- '█' represents walls.
- The program will output the solution in the console and save it as an image file.
