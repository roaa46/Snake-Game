# Snake Game

A simple and classic **Snake Game** built using **JavaFX**. The player controls the snake to collect food, and the snake grows longer with each food item consumed. Avoid collisions with the walls or the snake's own body to keep the game going!

## Features

- **Classic Gameplay**: Navigate the snake and eat food to score points.
- **Randomized Food**: Food appears in random locations with different colors.
- **Score Display**: The player's score is displayed in real-time.
- **Dynamic Speed**: The game becomes faster as the snake grows.
- **Game Over Detection**: Handles boundary collisions and self-collisions.
- **Arrow Key Controls**: Use `UP`, `DOWN`, `LEFT`, and `RIGHT` keys for movement.

## Controls

| Key         | Action         |
|-------------|----------------|
| `UP Arrow`  | Move up        |
| `DOWN Arrow`| Move down      |
| `LEFT Arrow`| Move left      |
| `RIGHT Arrow`| Move right     |

## Prerequisites

- Java 8 or higher
- JavaFX library

## How to Run

### Option 1: Using the Executable File

If you prefer a quicker way to run the game, you can use the precompiled executable file:

1. Download `snake-game.exe` from the releases section of the repository.
2. Run the `.exe` file directly to start the game.

### Option 2: Using Command Line (JavaFX)

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/snake-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd snake-game
   ```
3. Compile and run the application:
   ```bash
   javac -d . src/org/example/app/HelloApplication.java
   java org.example.app.HelloApplication
   ```
