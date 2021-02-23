# Duffing Oscillator
Python code and thorough documentation on solving the Duffing oscillator; this project was completed in 2017 as part of Computational Physics 2 at the University of Waterloo.

The Duffing oscillator is a second order, nonlinear, chaotic oscillator. We will solve it, and it will be shown what numerical method was chosen as well as how it was implemented.  The chaotic behaviour of this oscillator will also be discussed by showing plotsand discussing stability and convergence of the solution.

<img src="https://latex.codecogs.com/gif.latex?\LARGE&space;\kappa&space;\ddot{x}&space;&plus;\delta&space;{\dot{x}}&space;&plus;\alpha&space;x&plus;\beta&space;x^{3}=\gamma&space;\cos(\omega&space;t)" title="\LARGE \kappa \ddot{x} +\delta {\dot{x}} +\alpha x+\beta x^{3}=\gamma \cos(\omega t)" />

$\kappa \ddot{x} +\delta {\dot{x}} +\alpha x+\beta x^{3}=\gamma \cos(\omega t)$

The Duffing oscillator, named after Georg Duffing (1861–1944), is represented by a non-linear, second order differential equation. This equation has no exact analytic solution and therefore must be approximated using perturbation theory, or solved numerically. The Duffing oscillator is different from other oscillators due to it's restoring force, which is not proportional to it's extension distance (this refers to the $x^3$ term).

Through nonlinear analysis, it was determined that a trapezoidal method would be stable for this equation, however, to converge we would have to take a step size of $h^{3}$. As it was determined we could find a stable, convergent method that is second order in time, we then must implement numerical scheme for the Duffing oscillator. A Newton-Raphson method was used to linearize the equation.
