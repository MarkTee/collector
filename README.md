# Collector
![Screenshot of Collector](/screenshot.png?raw=true)

Collector is a small game implemented in the Jack programming language.

The goal of the game is to collect as many of the items (the hollow squares) as 
possible, while avoiding the circular enemies.

The game is controlled using the arrow keys.

## Installation/Build Instructions
The required compiler and virtual machine simulator (as well as instructions on
their use) can be downloaded for free 
[from the nand2tetris website](https://www.nand2tetris.org/software). Then use 
the following steps to run the game:

1. Use JackCompiler to compile this repo's .jack files.
2. Start VMEmulator.
3. In the emulator, click `File -> Load Script` and select the directory
containing the compiled .vm files.
4. Click "Yes" when asked if you'd like to use the built-in OS functions.
5. Click `View -> Animate -> No Animation` to ensure the game runs at
full-speed.
6. Press F5.

## About
Jack is a small custom language designed for the Nand2Tetris course. This game 
was written to learn more about Jack before writing a compiler for it.
