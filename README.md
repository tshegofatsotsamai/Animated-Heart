# Animated Heart - Python Turtle

A simple creative-coding project built with Python Turtle that generates a colourful geometric heart using mathematical curves, trigonometry, and repeated radial patterns.

This project was created as a small demonstration of Python programming, mathematical modelling, and graphical drawing using the built-in "turtle" module.


## Preview

The program generates a heart-shaped pattern on a black canvas using multiple randomly selected colours.

Each point along the heart curve is connected with a series of radial strokes, creating a colourful decorative effect.


## Technologies Used

* Python 3
* Turtle Graphics
* Math
* Random


## How It Works

The heart is generated using a parametric mathematical equation.

For each of 120 points around the curve, the program calculates an 'x' and 'y' coordinate using trigonometric functions:

```
x = 16 * (math.sin(angle) ** 3) * 15

y = (
    13 * math.cos(angle)
    - 5 * math.cos(2 * angle)
    - 2 * math.cos(3 * angle)
    - math.cos(4 * angle)
) * 15
```

The Turtle moves to each calculated coordinate and draws a series of short radial lines. A random colour is selected for each point from a predefined colour palette.

This combination of:

* Mathematical equations
* Trigonometric functions
* Iteration
* Randomisation
* Turtle graphics

produces the final visual effect.


## Features

* Mathematical heart-shaped curve
* Randomly selected colours
* Radial decorative patterns
* Turtle-based graphics
* Uses trigonometric mathematics
* Runs locally with standard Python

---

## Getting Started

- You need **Python 3** installed on your computer.
- Clone the repository:
                       git clone https://github.com/tshegofatsotsamai/animated-heart.git
- Navigate into the project:
                            cd animated-heart
- Run the program:
                  python heart.py

A Turtle graphics window will open and display the generated heart.


This project provided practice with:

* Python loops
* Functions from the 'math' module
* Trigonometric calculations
* Coordinate-based drawing
* Random number generation
* Turtle graphics
* Translating mathematical equations into visual patterns

A small Python creative-coding project exploring the intersection of programming, mathematics, and visualisation.
