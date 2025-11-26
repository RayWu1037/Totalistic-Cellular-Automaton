# Totalistic Cellular Automaton – 1D Simulation in C

## Overview

This project is a 1D totalistic cellular automaton implemented in C.
The program updates a row of cells over time based on a totalistic rule
and prints each generation so you can visualize how patterns evolve.

I built this project for a CS course to practice C programming,
arrays, loops, and working with simple simulation rules.

## Features

- Simulates a 1D totalistic cellular automaton
- Uses an initial configuration of cells (for example from the file `p01`)
- Updates the row of cells for multiple generations
- Prints each generation so patterns can be observed in the terminal
- Lets you experiment with different rules and starting patterns

## Technologies Used

- C programming language
- Arrays and loops
- Basic file I/O (for loading pattern/rule data, if applicable)

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/RayWu1037/Totalistic-Cellular-Automaton.git
cd Totalistic-Cellular-Automaton
cd "project-1-Totalistic Cellular Automaton (Coding in C A Total Cell-ebration!)"

### 2. Compile the program
gcc -std=c11 -Wall -Wextra -o demo main.c


On WSL/Linux this will create an executable called demo.
On Windows it will create demo.exe.

### 3. Run the program
./demo          # or: ./demo.exe on Windows

The program reads an initial pattern (for example from p01) and
prints each generation of the cellular automaton to the terminal.

## Example Usage

A typical run looks like this:

The program loads the starting pattern.

It applies the totalistic rule to compute the next generation.

Each generation is printed, row by row, so you can see the pattern evolve over time.

You can modify the starting pattern or the rule in the source code (or input file)
to see different behaviors.

## Project Structure

main.c – Main C source file that runs the simulation

p01 – Example input file with an initial pattern or rule data

demo / demo.exe – Compiled executable

README.md – This file

## Video Demo

I recorded a short demo video with audio narration that shows how to
open the GitHub repository, compile the program in WSL, and run the simulation.

### Watch the demo video here:
https://drive.google.com/file/d/1kLKn8tw__KXdV5yaxn0sUoE4WFo_k-pI/view?usp=drive_link
