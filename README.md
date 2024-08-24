# Snake Game

This is a classic Snake game implemented in Java. The game features a simple graphical interface where the player controls a snake to eat apples and grow longer while avoiding collisions with walls and itself.

## Features

- **Graphical User Interface**: The game is presented with a simple, easy-to-understand graphical interface.
- **Random Apple Generation**: Apples appear randomly on the screen, and the snake grows longer each time it eats one.
- **Score Tracking**: The player's score increases with each apple eaten.
- **Game Over Conditions**: The game ends if the snake runs into the walls or itself.

## Requirements

- **Java Development Kit (JDK)**: Make sure you have JDK installed on your machine. You can download it from [Oracle's website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/snake-game.git
    ```

2. Navigate to the project directory:

    ```bash
    cd snake-game
    ```

3. Compile the Java source files:

    ```bash
    javac -d bin src/org/example/*.java
    ```

    - This command compiles all the `.java` files in the `src/org/example` directory and outputs the compiled `.class` files into the `bin` directory.

4. Run the Snake Game:

    ```bash
    java -cp bin org.example.SnakeGame
    ```

    - This command runs the `SnakeGame` class using the compiled bytecode in the `bin` directory.

## How to Play

- Use the **arrow keys** on your keyboard to control the direction of the snake:
  - **Up Arrow**: Move up
  - **Down Arrow**: Move down
  - **Left Arrow**: Move left
  - **Right Arrow**: Move right
- The objective is to eat the red apples that appear randomly on the screen. Each time the snake eats an apple, it grows longer, and the score increases.
- The game ends if the snake collides with the walls or itself.
