# About

PyPlane is a free software for phase plane analysis of second order dynamical
systems written for PYTHON >= 3.8 and PyQT5 (compare MATLAB's
[pplane](https://www.mathworks.com/matlabcentral/fileexchange/61636-pplane)). It
is published under the GNU GENERAL PUBLIC LICENSE Version 3.

![Screenshot](pyplane/resources/pyplane_screenshot.png?raw=true)

## Features:

* Vector fields and streamlines for second order nonlinear dynamical systems of
  the form x'=f(x,y), y'=g(x,y)
* Forward and backward solution trajectories for arbitrary initial conditions in
  the phase plane
* Time dependent solutions x(t) and y(t)
* 3D visualization t(x,y)
* Nullclines
* Find equilibrium points and calculate the corresponding Jacobian
* Linearize a system around equilibrium points, characterize and plot
  eigenvectors
* Add arbitrary function into the phase plane area (i.e. contour lines of
  Ljapunov-functions)
* An optionally installed and accessible LaTeX/dvipng environment produces much
  prettier results in the linearization tabs. If no LaTeX is installed, the
  program is still fully functional.
* Several example systems are shipped with PyPlane. You find them in the
  directory `library`. Load them via "Open - From File" or by pressing STRG+O

**Please don't hesitate to report bugs, comments, or suggestions!**

# Running PyPlane

PyPlane runs either natively in a fully functional Python environment under
Linux/ Windows/ OSX or as a stand-alone executable under MS Windows.

## Running natively under Python

### Installation using pip

If you have `pip` available in your Python installation PyPlane can be easily
installed as follows:

1. Clone the repository
2. Change into the root directory of the repository
3. Execute `pip install .`

PyPlane can then be invoked from the command line by executing the command
`pyplane` or via `python -m pyplane`

*Note:* When some important missing features are implemented PyPlane will be
also available via PyPi.

### Executing from the source code

If the following pre-requisites are fullfilled you may invoke PyPlane directly
from the repository:

**Pre-requisites:**

* Python 3.8, 3.9
* NumPy (tested under version 1.20, 1.21)
* SciPy (tested under version 1.6, 1.7)
* Matplotlib (tested under version 3.3, 3.4)
* SymPy (tested under version 1.7, 1.9)
* PyQt5 (tested under version 5.13, 5.15)

**Launch of pylane**

1. Clone the repository
2. Change into the root directory of the repository
3. Execute `python run_pyplane.py` or `python -m pyplane`




