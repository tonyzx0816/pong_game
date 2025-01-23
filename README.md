Pong Game

This repository contains the code for a classic Pong game implemented in Python using the Turtle graphics library.
*************************************
Features:

1. Two-Player Gameplay: Players control paddles using keyboard controls (WASD for left player, arrow keys for right player).

2. Responsive Controls: Smooth and controlled paddle movement with adjustable speed.

3. Score Tracking: Accurate scorekeeping for both players, displayed on the screen.

4. Realistic Physics: Accurate ball physics with realistic bounces off walls and paddles.

5. Screen Boundaries: Paddles are restricted to the playing area, preventing them from moving off-screen.

6. Clean Interface: A simple and visually appealing interface with a clear midline.
*************************************
Controls

Left Player:

    W: Move paddle up

    S: Move paddle down
    
Right Player:

    Up Arrow: Move paddle up

    Down Arrow: Move paddle down
*******************************************
Project Structure

main.py: Contains the core game logic, event handling, and game loop.

paddle.py: Defines the Paddle class, handling paddle movement, speed, and screen boundary checks.

ball.py: Defines the Ball class, handling ball movement, speed, and collision detection.

scoreboard.py: Defines the Scoreboard class, responsible for tracking and displaying the score.
