Overview

This repository contains a classic implementation of the Snake Game using Python's turtle module. The game involves controlling a snake to eat food while avoiding collisions with the screen borders or its own body. As the snake consumes food, it grows in size, and the player's score increases. The objective is to achieve the highest score possible.

Features

Simple Controls: Use W, A, S, and D keys to control the snake's movement.

Dynamic Gameplay: Snake grows as it eats food, and the game speed increases.

Randomized Elements: Food position, colors, and shapes are randomized for variety.

High Score Tracking: Keeps track of the highest score achieved during the session.

How to Play

Run the Python script.

Use the following keys to control the snake:

W for up

A for left

S for down

D for right

Guide the snake to eat the food while avoiding:

Collisions with the screen borders.

Collisions with its own body.

The game ends if the snake collides with the screen borders or itself.



Gameplay

Score: Increases by 10 points for every food item eaten.

High Score: Updates if the current score surpasses the previous high score.

Speed: The snake's speed increases as the score increases, adding a challenging element.

Customization

You can customize various elements of the game:

Screen Dimensions: Modify wn.setup(width, height) to change the game window size.

Snake and Food Colors: Adjust the colors and shapes lists for different visual styles.

Speed: Change the delay variable to alter the initial speed.

Challenges for Advanced Players

Here are a few challenges to enhance your experience:

Add Obstacles: Introduce barriers in the game area that the snake must avoid.

Multiple Levels: Implement levels with increasing difficulty.

Power-Ups: Add special items that temporarily boost the score or slow down the game speed.

Multiplayer Mode: Enable two players to control separate snakes.

Acknowledgments

Python's turtle module for its simplicity in creating graphical applications.

The classic Snake Game concept, which remains a favorite across generation
