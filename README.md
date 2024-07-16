Conway's Game of Life:
  - This repository contains implementations of Conway's Game of Life using different design patterns.

Contents:
  - classpath: Eclipse classpath configuration file.
  - project: Eclipse project configuration file.
  - dudraw (1).jar: External library used for drawing.
  - src/: Source code directory containing different implementations of the Game of Life.
  - bin/: Compiled Java classes.

Implementations:
  - Original Version: Basic implementation of Conway's Game of Life.
  - Singleton Pattern: Implementation using the Singleton design pattern.
  - Command Pattern: Implementation using the Command design pattern.
  - Observer Pattern: Implementation using the Observer design pattern.
  - Visitor Pattern: Implementation using the Visitor design pattern.

Prerequisites:
  To run this project, you'll need the following:
  - Java Development Kit (JDK) 8 or higher.
  - An IDE that supports Java, such as Eclipse or IntelliJ IDEA.
  
  Setup:
  - Clone the repository
  - Open the project in your IDE:
    - If using Eclipse, you can import the project as an existing project.
    - If using IntelliJ IDEA, you can open the project directory directly.

  Add the external library:
  - Add dudraw (1).jar to your project's build path.

How It Works:
- Conway's Game of Life is a cellular automaton devised by mathematician John Conway. The game consists of a grid of cells that can live, die, or multiply based on a few mathematical rules.

  Rules:
  - Any live cell with two or three live neighbours survives.
  - Any dead cell with three live neighbours becomes a live cell.
  - All other live cells die in the next generation. Similarly, all other dead cells stay dead.
