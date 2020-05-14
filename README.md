# CS 534: Artificial Intelligence

Projects and notes for the WPI graduate class CS 534: Artificial Intelligence.

Projects for this class are separated into their own repositories, and added
here as submodules. To clone these as well, do:

```
$ git submodule init
$ git submodule update
```

## Project 1

Project 1 is made up of two parts. For the first part, we use both A* and
random-restart hill-climbing with a variable number of sideways moves to solve
the heavy n-queens problem.

For the second part, we use hill climbing and a genetic algorithm to solve a
simplified urban planning problem by laying out industrial, commercial, and
residential zones in an optimal placement.

## Project 2

Project 2 is a Python project that clusters two-dimensional data based on an
Expectation-Maximization algorithm.

## Project 3

Project 3 is made up of two parts:

  - A Python program that navigates a two-dimensional gridworld with obstacles
	and rewards at various grid points. It uses Q learning to iteratively get
	better at navigating the grid world until it converges on the optimal
	solution.

  - Another Python program that extends the Q learning algorithm to control a
	simulated robotic delivery truck. The program learns when to schedule
	departures of the truck from a warehouse to maximize the number of packages
	delivered and minimize wasted time.

## Final Project

The final project is a TypeScript project for playing a simple word game called
Jotto. We implemented a greedy best response agent to play the game, based on
English language word frequencies.
