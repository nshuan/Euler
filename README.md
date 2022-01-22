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

### Requirements
The program was written with Python3, so the device must have Python3 (3.8.10 or later version) installed

## Step by step guide
This guide will help you to run the program normally without reading the code.
However, there are still tips written as comments in each file that help you to read the code easier.

### `main.py` file
This is the main file of the program and it's function is to solve a first order ODE with 3 methods
Forward Euler, Backward Euler, Trapezoidal.

* Step 1: Enter required data as the tutorial in the `Input/input.txt` file
> All values in the same line must be splitted by a comma.
> In the first line, either `^` or `**` are acceptable, but `e^x` must be replaced by `exp(x)`.

* Step 2: Run:

```bash
python main.py
```

* Step 3: Check files `Output/output.txt` and `Output/output.png` for the answer

### `main_hcomparation.py` file
Use only 1 method to solve an ODE with more than 1 step h and plot

* Step 1: Run:

```bash
python main_hcomparation.py
```

* Step 2: Enter f(x, y):

```bash
y' = f(x, y) = 
```

* Step 3: Enter x0, y0, xn in one line and list of step h in the next line, all values in the same line are splitted by commas:

```bash
y' = f(x, y) = -10*y
Enter x0, y0, xn: 0, 1, 3
Enter list of step size (h): 0.01, 0.05, 0.2, 0.21
```

* Step 4: Enter number that present the method used:
> `0` for Forward Euler method,
> `1` for Backward Euler method, 
> `2` for Trapezoidal method

```bash
"y' = f(x, y) = -10*y
Enter x0, y0, xn: 0, 1, 3
Enter list of step size (h): 0.01, 0.05, 0.2, 0.21
Method used: 0"
```
