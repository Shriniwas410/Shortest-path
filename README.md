# Shortest-path

This repository contains a Python script for finding the shortest path of connections between two actors using breadth-first search.

# Description

The script uses data from CSV files containing information about people, movies, and the stars of those movies. It implements a breadth-first search algorithm to find the shortest path of connections between two actors, where each connection is a movie that both actors starred in. The file in ```small``` directory contain less amount of data. The files in ```large``` directory contain large amount of data.

# Features

- Loading data from CSV files into memory.
- Finding the shortest path of connections between two actors.
- Handling cases where there are multiple people with the same name.
- Handling cases where there is no connection between two actors.
  
# How to Use

1. Clone this repository.
2. Run the script and input the names of the two actors when prompted.
   
# Requirements

- Python 3.6 or above
- Libraries: csv, sys
  
# Code Structure

- The script first imports the necessary libraries and defines the Node, StackFrontier, and QueueFrontier classes.
- It then loads data from CSV files into memory.
- The script prompts the user to input the names of two actors.
- It finds the shortest path of connections between the two actors using a breadth-first search algorithm.
- If a connection is found, the script prints the degrees of separation and the movies that connect the actors.
- If no connection is found, the script prints "Not connected.