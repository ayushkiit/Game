# Flappy Bird Game (Java)

## Overview
This project is a simple Flappy Bird clone developed in Java using the Swing framework. The game features a bird character that moves through an obstacle course of pipes, controlled using the spacebar. The objective is to score as many points as possible by passing through gaps between the tubes without colliding.

## Features
- **Smooth bird movement** with gravity and jump mechanics.
- **Obstacle generation** using procedurally created pipes.
- **Score tracking** with a high score display.
- **Game restart functionality** after collision.
- **Optimized rendering** using `Graphics2D`.
- **Object-Oriented Design Patterns** such as Strategy and Proxy.

## Installation & Execution
### Prerequisites
- Java Development Kit (JDK) 8 or higher.
- Any Java-supported IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans) or a simple text editor with a command-line terminal.

### Steps to Run
1. Ensure you have `Game.java` and required image assets (`bird.png`, `TubeBody.png`, `backk.jpg`) in the same directory.
2. Compile the Java file:
   ```sh
   javac Game.java
   ```
3. Run the game:
   ```sh
   java Window
   ```

## How to Play
- Press `Enter` to start the game.
- Press the `Spacebar` to make the bird jump.
- Avoid colliding with the pipes.
- Your score increases as you pass through gaps in the tubes.
- The game ends when the bird collides with a tube or the screen boundary.
- Press `Enter` to restart the game after a collision.

## Code Structure
### Classes
1. **`Game`** - Manages the game loop, rendering, and collision detection.
2. **`Bird`** - Represents the player's character, handles movement and jumping.
3. **`Tube`** - Represents individual pipe obstacles.
4. **`TubeColumn`** - Manages the collection of pipes and their movement.
5. **`Window`** - Creates the game window.
6. **`Controller`** - Handles keyboard input.
7. **`ProxyImage`** & **`RealImage`** - Implements the Proxy design pattern for optimized image loading.
8. **`GameObject`** - Abstract class serving as the base for all game objects.

## Future Improvements
- Add sound effects for jumping and collision.
- Implement additional difficulty levels.
- Optimize collision detection.
- Add a main menu and pause functionality.

## License
This project is open-source and free to use for educational and personal projects.

## Author
Developed by Virat
