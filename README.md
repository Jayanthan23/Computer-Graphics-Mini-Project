# Rubik's Cube Solver

This project is a Rubik's Cube solver implemented in Python. It provides a command-line interface (CLI) to solve a standard 3x3 Rubik's Cube using a well-known algorithm. The program can take user inputs representing the cube's state and then output the series of moves required to solve it.

## Features

- *Input Validation:* Ensures that the provided cube state is valid before attempting to solve it.
- *Solver Algorithm:* Utilizes an efficient algorithm to solve the cube.
- *Command-Line Interface:* User-friendly CLI for inputting cube states and receiving the solution.

## Installation

1. *Clone the Repository:*
   bash
   git clone https://github.com/yourusername/rubiks-cube-solver.git
   cd rubiks-cube-solver
   

2. *Set Up the Environment:*
   - Make sure you have Python installed (Python 3.6+ recommended).
   - Install the required packages using pip:
     bash
     pip install -r requirements.txt
     

## Usage

1. *Run the Solver:*
   bash
   python rubiks_cube_solver.py
   

2. *Input the Cube State:*
   - The program will prompt you to input the state of the Rubik's Cube.
   - Enter the colors of each face in a specific order (instructions will be provided by the program).

3. *Get the Solution:*
   - The program will output a sequence of moves to solve the cube.

## Example

bash
$ python rubiks_cube_solver.py
Input the colors of the cube in the following order: ...
Solution: U R2 F B R B2 R U2 L B2 R U' D' R2 F R' L B2 U2 F2


## Algorithms Used

This solver uses the *CFOP (Cross, F2L, OLL, PLL)* method, one of the most popular algorithms for solving the Rubik's Cube.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.




