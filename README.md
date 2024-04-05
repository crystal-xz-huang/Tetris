# Tetris
A basic implementation of [Tetris](https://tetris.com/play-tetris) in C

## Introduction

This simple game of _Tetris_ takes place on a 2D field, where players must fit together descending shapes to make lines.

You can move a piece left (a) and right (d), drop it down (one step with s or all the way with S), and rotate it (r and R).

Once a piece hits the bottom, another piece will appear at the top of the field.

Any horizontal lines in the field that become completely filled will be cleared, and points will be awarded to the player's score based on how many lines are cleared at the same time.

To get a feel for this game, try it out in a terminal!

## Commands

r - Rotate the current piece clockwise	
R - Rotate the current piece counter-clockwise	
n - Remove the current piece and add a new one at the top of the field	
s - Move the current piece down one row.	
S - Drop the current piece to the bottom of the field	
a - Move the current piece to the left by one column	
d - Move the current piece to the right by one column	
p - Place the current piece into the field	
c - Allow the player to choose which piece will drop next	
? - Output the current state of the game	
q - Quit the game	
