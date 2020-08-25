# DuffingOscillator
Python code and thorough documentation on solving the Duffing oscillator; this project was completed in 2017.

The Duffing oscillator is a second order, nonlinear, chaotic oscillator. We will solve it, and it will be shown what numerical method was chosen as well as how it was implemented.  The chaotic behaviour of this oscillator will also be discussed by showing plotsand discussing stability and convergence of the solution.

<img src="https://render.githubusercontent.com/render/math?math=\kappa \ddot{x} + \delta {\dot{x}} + \alpha x + \beta x^{3} = \gamma \cos(\omega t)">

The Duffing oscillator, named after Georg Duffing (1861–1944), is represented by a non-linear, second order differential equation. This equation has no exact analytic solution and therefore must be approximated using perturbation theory, or solved numerically. The Duffing oscillator is different from other oscillators due to it's restoring force, which is not proportional to it's extension distance (this refers to the $x^3$ term).
