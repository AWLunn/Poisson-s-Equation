# Poisson-s-Equation

We investigate Poisson’s Equation within an electrostatic system comprising parallel, infinitely long grounded metal plates separated by a distance of 5 centimeters. Positioned at the top and bottom of the system, these plates are interconnected along their sides through narrower metal strips, forming a rectangular channel. They are set to a constant potential of 4 Volts.

The first task is to analyze this boundary value problem using both analytic and numerical methods. To achieve this, we employ a numerical technique called Jacobi iteration. This method provides a numerical solution to Laplace's equation in 2D. The resulting solution will be visualized using a contour plot, facilitating a comparison with the derived analytic solution.

After looking at the instance with no charge density term, we move on to different scenarios involving various charge densities between the plates. Once again using the Jacobi iteration, we investigate the impact of three different charge densities to determine what variations they may have on the system.

Finally, we focus on a specific scenario where the charge density is set to a particular value. Here, we employ a direct matrix solution technique instead of Jacobi iteration. Consequently, we compare this solution to our results from the Jacobi iteration with the same charge density.

By comparing solutions governed by Poisson’s Equation within the setup of parallel metal plates we can determine the advantages and limitations of these computational methods in modeling Poisson's Equation. Through these simulations, we aim to extend our knowledge of partial differential equations and their implications.

Authors: Alec Lunn, Trace Harms
