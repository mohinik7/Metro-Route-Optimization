# Metro Route Optimization

This project is a Java-based metro route optimization system designed to facilitate efficient navigation across a metro network. It offers features like route planning, alternative route suggestions, fare calculations with discounts, and real-time route changes.

## Features
1. **Route Details**: Displays the optimal route between two stations using Dijkstra's algorithm.
2. **Alternative Routes**: Finds all possible routes between two stations.
3. **Minimal Transfer Path**: Identifies routes with minimal transfers, including fare calculations.
4. **Fare Calculation with Discounts**: Supports fare adjustments for students and senior citizens.
5. **Route Change**: Allows passengers to modify their journey by selecting a midway station and a new destination.
6. **Passenger Management**: Tracks passenger information, such as name, age, and bill amount.

## Technology Stack
- **Language**: Java
- **Data Structures**: Graphs (Adjacency List), Priority Queue, and HashMap
- **Algorithm**: Dijkstra's Algorithm for shortest path calculation

## How to Run
1. Clone this repository.
2. Compile the code using `javac MetroRouteOptimization.java`.
3. Run the program with `java MetroRouteOptimization`.
4. Follow the on-screen prompts to input passenger details and select actions like finding routes or changing destinations.

## Usage Examples
1. **Displaying Route Details**:
   - Input the start and end station names.
   - View the shortest path and estimated fare.

2. **Finding Alternative Routes**:
   - Input the start and end station names.
   - Get a list of alternative paths with their respective fares.

3. **Changing Route**:
   - Provide a midway station to stop at and a new destination.
   - The system updates the route and fare accordingly.

## Future Enhancements
- Integration with a user-friendly graphical interface.
- Real-time data updates for metro schedules and maintenance.
- Support for multi-modal transport systems (e.g., buses and trains).


