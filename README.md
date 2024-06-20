# Travel Planner

Travel Planner is a command-line application that calculates the shortest path between cities based on user preferences for either the fastest or the cheapest route. It uses Dijkstra's Algorithm to determine the optimal path and provides an interactive visualization of the route on a Google Map.

## Features

- *Shortest Path Calculation*: Implements Dijkstra's Algorithm to find the shortest path based on travel time or cost.
- *Data Parsing*: Reads and interprets location and route data from CSV files, dynamically linking routes to their respective cities.
- *Interactive Map Visualization*: Generates an HTML file with embedded JavaScript to visualize the travel route on Google Maps.

## Usage

### Command Line Arguments

The program can be run with command line arguments or interactively by providing the required information.

1. *Cities File*: Filename containing cities data (CSV).
2. *Routes File*: Filename containing routes data (CSV).
3. *Output File*: Filename for the output HTML file.
4. *Origin*: Starting city for the route.
5. *Destination*: Destination city for the route.
6. *Preference*: Travel preference ("fastest" or "cheapest").
