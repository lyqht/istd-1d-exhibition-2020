---
layout: video
show_meta: false
title: Snake game
subheadline: 50.002 Team 14-3
tags:
    - post format
categories:
    - compstruct
iframe: <iframe src="rc="https://drive.google.com/file/d/1uYXOO0nNTdXtROo81WJuGhqVuynZlnVh/preview" width="640" height="480"></iframe>
related_image: https://lh3.google.com/u/0/d/1qG7LwDsgc9zg6DHhBpoW1_PIYi2J-pwL=w300-h300-p-k-nu-iv1
---


  

### Description

Objective: Move the Snake around to eat fruits that are randomly spawned on the LED matrix and make the Snake grow. Once the Snake grows to 10 units long, the player wins. If the Snake collides with itself or the wall, the player loses.

Control Buttons

1. Yellow: Reset and Start

2. Blue: Move Up

3. Red: Move Left

4. Green: Move Right

5. White: Move Down

Gameplay: The Snake starts out as 2 LED red lights. A fruit with LED green lighting will appear randomly on the 32 by 64 LED matrix. Eating a fruit adds one red LED light to the Snake’s body. The Snake’s maximum length is 10 LED red lights long.

States: Once the snake reaches 10 LED lights long, the game enters FREEZE state from CHECK WIN. Everything on the screen will be erased to show the player has won the game.

If the snake collides with itself or the wall, the internal logic transitions from CHECK LOSE to FREEZE, where the snake is frozen on the screen and not erased like when winning the game.

The reset button can now be pressed to restart the game.

### Poster

<iframe src="https://drive.google.com/file/d/1qG7LwDsgc9zg6DHhBpoW1_PIYi2J-pwL/preview" width="640" height="480"></iframe>
