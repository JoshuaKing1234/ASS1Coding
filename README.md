
# Monte Carlo Minimization with Fork-Join Framework

This Java program implements the Monte Carlo minimization algorithm using the Fork-Join framework to find the global minimum of a function within a specified grid area. The program samples random points, evaluates their values, and searches for valleys with the lowest values.

## Table of Contents

- [Introduction]
- [Usage]
- [Getting Started]
- [License]

## Introduction

The Monte Carlo minimization algorithm aims to find the global minimum of a function by randomly sampling points within a given grid area and evaluating their values. This program utilizes the Fork-Join framework to parallelize the computation, dividing the task into smaller sub-tasks that can be processed concurrently.

## Usage

To run the program, provide the required command line arguments in the following format:

```sh
java -classpath path/to/your/classpath MonteCarloMini.MonteCarloMinimization <rows> <columns> <xmin> <xmax> <ymin> <ymax> <search_density>
```

- `rows`: Number of rows in the grid.
- `columns`: Number of columns in the grid.
- `xmin`, `xmax`: Range of x coordinates for the grid.
- `ymin`, `ymax`: Range of y coordinates for the grid.
- `search_density`: Density of Monte Carlo searches per grid position (usually less than 1).

## Getting Started

1. Clone this repository to your local machine.
2. Compile the Java source code:
   ```sh
   javac -classpath path/to/your/classpath *.java
   ```
3. Run the program with the appropriate command line arguments:
   ```sh
   java -classpath path/to/your/classpath MonteCarloMini.MonteCarloMinimization <rows> <columns> <xmin> <xmax> <ymin> <ymax> <search_density>
   ```

## License

This project is licensed under MIT

---

