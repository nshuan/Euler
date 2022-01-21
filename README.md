# Euler
Euler methods to solve ODEs

## Setup the environment
> From this point, the word "lib" will be used as "library" and "libs" as "libraries"

Necessary libs for this program are listed below:
* sympy
* matplotlib
* wolframalpha (This lib is used to get the exact solution from Wolfram Alpha)

### Install libs
To install these libs, run these commands in terminal:

```bash
pip install sympy matplotlib wolframalpha
```

### Arrange folder
For the code to run normally, all files except for input and output files should be placed in the same folder

## Step by step guide
> This guide will help you to run the program normally without reading the code.
> However, there are still tips written as comments in each file that help you to read the code easier.

### `main.py` file
> This is the main file of the program and it's function is to solve a first order ODE with 3 methods
> Forward Euler, Backward Euler, Trapezoidal.

* Step 1: Enter required data as the tutorial in the `Input/input.txt` file
> All values in the same line must be splitted by a comma.
> In the first line, either `^` or `**` are acceptable, but `e^x` must be replaced by `exp(x)`.

* Step 2: Run:

```bash
python main.py
```

* Step 3: Check files `Output/output.txt` and `Output/output.png` for the answer
