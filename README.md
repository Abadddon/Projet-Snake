## THE DEADLY SNAKE (2024)

## Overview
***
"The Deadly Snake !" is a Home-made version of the Snake game. The goal was to create few games based on the well-known game Snake using Tkinter. 
![Snake Game Gif](https://i.gifer.com/Q2DZ.gif)


## Table of contents
***
1. Prerequisites
2. Getting started
3. Graphical interface main windows walkthrought
4. Gameplay 
5. Features
6. Acknowledgments
7. Authors


## 1. Prerequisites
***
• Python 3.10


## 2. Getting started
***
• Insure Python is installed

• Install the librairies : download the LIBRARIES1 document and install it typing "pip install -r LIBRARIES1.txt" 

• Download the folder with the pictures and uncompress it (im_snake_zip.zip)

• Put the path of the pictures in the code


## 3. Graphical interface main windows walkthrought
***
• Main menu : first window launched by the program, allows the player to access the game selection window, score board window, command explanation window and game rules window.

• game selection window : allows the player to select a game out of three choices by clicking on a button. A countdown window (3 seconds) will then appear before the game window is launched.

• score board window : allows the player to see his last five scores and current high score for each game.

• command window : gives a brief description on how to control your snake in all three games.

• game rules window : gives a brief description of each game's rules and goals.

• game1 window : window to play the classic snake game , accessible by pressing the game1 button in game selection window.

• game2 window : window to play the the snake vs game, accessible by pressing the game2 button in game selection window.

• game3 window : window to play the vocal control snake , accessible by pressing the game3 button in game selection window.


## 4. Gameplay 
***
• First select a game in the game select window

• Then click on the window to start the game

• Use arrow keys to navigate the snake by guiding it upwards, downwards, left and right in Games 1 and 2.

• Use your voice to navigate the snake, guiding it with the key words "up", "down", "left" and "right" in Game 3.

• The game concludes if the snake collides with the screen borders or itself, and also if another Snake in Game 2 collides with yours.

• Navigate the snake within the map boundries to eat apples enabling the snake's growth.

• In Game 2 eating a golden apple will make the snake invincible for 5 seconds allowing it to terminate it's ennemies.

• Games 1 and 3 end either when the snake has eaten a certain amount of apples (here set to 20) (win) or when it dies (game over).

• Game 2 ends either when the snake has terminated all 5 ennemies (win) or when it dies (game over).

• WARNING : Game 2 is not yet operatinal, voice controls have been disabled. For testing game 3 please refere to Game 3 v2 notebook in this repository.
This notebook contains a prototype version of the game. It is operational but can crash the kernel after multiple program iterations.


## 5. Features
***
- [x] Graphical interface using Tkinter.
- [x] Other windows management and display.
- [x] Snake movement management.
- [x] Randomized food generation.
- [x] Snake length increases upon consuming food.
- [x] Snake ennemies appearance.
- [x] Status when game ends.
- [x] Score update and display.


## 6. Acknowledgments
***
We would like to thank the Tkinter community for providing a versatile library for creating graphical user interfaces in Python.
Additional thanks to the StackOverflow community for valuable insights and problem-solving support.
Special thanks to Mr.Descharrière for the Computer Science Lectures and continuous support during the project.


## 7. Authors
***
4th year engineering students in Robotics and Instrumentation (FRANCE) :

   • Baptiste LESQUERRÉ-CAUDEBEZ
   
   • Charlène BEZIER
