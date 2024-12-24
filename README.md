# VACUUMINATOR NAVIGATION SYSTEM
## Project Background
Originally a Python assignment for robot navigation, reimplemented in C for improved memory management, pointer manipulation, linked list data structures, and algorithm optimization.

## Core Components

### TASK 1: DISTANCE TO WALL
Calculates the distance from the robot ('X') to the nearest wall ('W').

### TASK 2: MOVEMENT HANDLER
Executes robot movement with collision detection, handles directions 'u'(up), 'd'(down), 'l'(left), 'r'(right), and updates world state.

### TASK 3: DIRT DETECTION
Generates the path from the robot to the most prioritized dirt ('D'), with priorities based on distance and direction.

### TASK 4: CLEANING PATH GENERATOR
Generates the full cleaning path for the robot, including backtracking if necessary, and returns the path to clean all accessible dirt.

### TASK 5: OPTIMAL CLEANER (BONUS)
Creates a function `optimal_vacuuminator(world)` that returns a list of moves to clean all the dirt in the world in the fewest moves possible. If the Vacuuminator is unable to clean all dirt, it returns `None`. Assumes the world is less than 6 tiles in width and length.

## Technical Implementation

### Data Structures
- **Linked Lists**: Path storage and backtracking
- **Dynamic Arrays**: World grid representation
- **Custom Memory Management**: Manual allocation/deallocation

### World Representation
- `X`: Vacuuminator position
- `W`: Wall
- `D`: Dirt
- `E`: Empty space

## Documentation
For detailed descriptions, examples, and task breakdowns, refer to `Task Description.md`.
