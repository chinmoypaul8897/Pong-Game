
# Pong Game

A classic Pong game built using Java, featuring a simple user interface, real-time gameplay, and keyboard controls for two players. This project leverages Java Swing for graphical rendering and event handling to provide an engaging experience.

## Features
- **Two-Player Mode**: Play with a friend, with each player controlling one paddle.
- **Real-Time Gameplay**: The game runs in real-time with smooth ball movement and paddle interaction.
- **Collision Detection**: The ball bounces off the top, bottom, and paddles.
- **Score System**: Tracks and displays the score for both players.
- **Keyboard Controls**:  
  - Player 1: Use `W` (up) and `S` (down) keys.  
  - Player 2: Use `Up Arrow` (up) and `Down Arrow` (down) keys.  

## Tech Stack  
- **Java 17**: Used to write the core logic for the game.  
- **Swing (JFrame and JPanel)**: Used for rendering the game interface.  
- **AWT**: For handling graphics and user input.  
- **Random**: For randomizing ball movement at the start of the game.  

## How to Play  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/chinmoypaul8897/Pong-Game.git  
   cd Pong-Game  
   ```  
2. Compile and run the game:  
   - Ensure you have **Java 17** installed.  
   - Use the following command to compile the project:  
     ```bash  
     javac PongGameJava/*.java  
     ```  
   - Run the game:  
     ```bash  
     java PongGameJava.PongGame  
     ```  
3. Use the keyboard to control the paddles:  
   - Player 1: `W` to move up, `S` to move down.  
   - Player 2: `Up Arrow` to move up, `Down Arrow` to move down.  

## Game Components  
### Ball  
The ball is the core element of the game. It moves around the screen, bouncing off the paddles and the edges. The `Ball` class handles the movement and collision detection.  
- **Movement**: The ball’s position is updated on every frame based on its velocity.  
- **Collision**: The ball bounces off the paddles and the top/bottom edges of the window.  

### Paddles  
Each player controls a paddle, which moves vertically along the screen. The paddle can be moved using the keyboard.  
- **Player 1 Paddle**: Controlled using the `W` and `S` keys.  
- **Player 2 Paddle**: Controlled using the `Up Arrow` and `Down Arrow` keys.  

### Score  
The `Score` class tracks and displays the score for both players. A point is awarded to Player 1 when the ball crosses Player 2's side, and vice versa.  
- The score is displayed at the top of the screen in a `Consolas` font.  

### Game Panel  
The `GamePanel` class is where most of the game logic resides, including:  
- **Game Loop**: Continuously updates the game state, moves the paddles, checks for collisions, and repaints the screen.  
- **Rendering**: Draws the paddles, ball, and score on the screen.  

### Game Frame  
The `GameFrame` class sets up the JFrame window that holds the game. It initializes the game panel and ensures the window behaves correctly.  

### Paddle  
The `Paddle` class represents the player’s paddle. It responds to keyboard input to move the paddle up or down and handles its drawing on the screen.  

## Project Structure  
- `PongGameJava/`  
  - `Ball.java`: Contains logic for the ball movement and collision.  
  - `GameFrame.java`: Sets up the main game window.  
  - `GamePanel.java`: Contains the game loop and handles rendering.  
  - `Paddle.java`: Manages paddle movements and interaction with the ball.  
  - `Score.java`: Manages and displays the score.  
  - `PongGame.java`: Main class to start the game.  

## Demo Video 



https://github.com/user-attachments/assets/b655649d-2128-4b5f-bf41-2d4805a5b39a



## Contact  
For any questions or suggestions, feel free to contact the project owner at [chinmoypaul8897@gmail.com](mailto:chinmoypaul8897@gmail.com).  

---  

Thank you for checking out the Pong Game! Enjoy playing!  

