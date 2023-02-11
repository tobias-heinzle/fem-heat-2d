# fem-heat-2d
Simple piecewise linear Finite Element Method for the heat equation in 2D with backward Euler and Crank-Nicolson time step.
The program implements zero Dirichlet boundary conditions and is configured for a model problem using a rectangular domain containing a cylinder. To change the domain, one also has to reimplement the is_on_boundary method, since it is tailored to the problem domain.
Based on the lectur notes of the Course " Numerics of Partial Differential Equations" WS2022 at the University of Vienna https://mat.univie.ac.at/~perugia/teaching.html and these lecture notes https://people.maths.ox.ac.uk/suli/fem.pdf.
