# C program for a Tic-Tac-Toe-Game
## Overview
This C program was written to play a game of Tic Tac Toe. It was written in Dev C++ code editor.
Tic-tac-toe, noughts and crosses, or Xs and Os is a game for two players who take turns marking the spaces in a three-by-three grid with X or O. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.
In this code, we are taking alternate input from each player, thereby asking them to specify the position for their mark. Whichever player manages in placing three of their marks in a horizontal, vertical, or diagonal row is the winner. 
I refered to the code from a youtube video [Youtube video](https://youtu.be/gSitgqAJn_I)

## Description of the header files used in the code
#include <stdio.h> : It has necessary information to include the input/output related functions in the program.

#include <conio.h> : It is used to provide console input/output.

#include <windows.h> : It contains declarations for all of the functions in the Windows API, all the common macros used by Windows programmers, and all the data types used by the various functions and subsystems.

#include <stdlib.h> : It includes functions involving memory allocation, process control, conversions and others.

## Description of the fuctions used in the code
Main() function: It inputs the choice from the user and marks that player's position with X or 0 for player 1 and player 2 respectively. If the position inputted by the user is already taken, it promts the user to input another position.

checkWin() function: It checks the whether the condition required for winning is satisfied and returns the result accordingly.

drawBoard() function: It is used to display the game name and the three-by-three grid.

## Output screenshots

<img width="947" alt="2022-05-03 (1)" src="https://user-images.githubusercontent.com/91649989/166426011-bf985b0c-c2ed-4bb3-9368-93d4c3c9f0d1.png">
<img width="941" alt="2022-05-03 (2)" src="https://user-images.githubusercontent.com/91649989/166426038-49883a30-27a1-402f-b42d-c07cc0cd841d.png">
