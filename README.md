
# Schrodinger-Equation

- The goal of this project is to solve the 1-D Schrödinger equation for a 1-D double-well potential by a numerical shooting method using 4th order Runge-Kutta method. 

- The [report](https://github.com/ShashankKumbhare/Schrodinger-Equation/blob/main/Project%20Final%20Report%20with%20code.pdf) contains the analysis of the problem, the methodology used, the [python code](https://github.com/ShashankKumbhare/Schrodinger-Equation/blob/main/code%20Project%20Final.ipynb) used, the results, and discussion.

- The Schrödinger equation is the fundamental quantum mechanical equation. However, only for a handful of cases it can be solved analytically, thus requiring a numerical method to solve for systems where no analytical solution exists.

- The shooting method is a numerical method to solve differential equations such as the Schrödinger equation where the boundary conditions are known and certain parameters to solve the equations must be found. 

- In this project, we study the parameter energy (E) as the eigenvalue of the system. The shooting method used in this project is the double-shooting method. In double-shooting method, we take the left & right boundary conditions as initial conditions of the equation as the starting points and shoot from both left & right side with defined initial values. Then we observe whether the solutions from left & right shooting comes close enough at some matching point. If this is the case, we then refine it further to a specified accuracy.

- In this project, the Schrödinger equation is solved for a 1-D double-well potential and later for a simple harmonic oscillator around x0, where x0 is one of the two bottoms of the double-well. To demonstrate the method's accuracy, we use a simple harmonic oscillator around x=0 as a test potential to compare the numerical solutions to their analytical counterparts. Overall, the results match the analytical solutions proving the shooting method to be a useful tool for obtaining numerical solutions for the Schrödinger equation.
