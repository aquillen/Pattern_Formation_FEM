Python notebooks that illustrate some pattern formation models (mostly on triangular meshes and without periodic boundaries).

<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/fem_brus_circle.ipynb"> 
fem_brus_circle.ipynb </a>: Brusselator reaction diffusion equation on a triangular mesh of a circle.  The boundary condition is Neumann with both fields having normal component of gradient equal to zero. The system is integrated with the scikit-fem finite element package. 


<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/fem_complex_ginzburg_landau.ipynb">
fem_complex_ginzburg_landau.ipynb: </a> Integrating the Complex Ginzburg Landau equation on a triangular mesh of a circle with the Neumann boundary condition. 


<br>
<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/fem_swift_hohenberg.ipynb">
fem_swift_hohenberg.ipynb: </a> Integrating the Swift-Hohenberg model on a triangular mesh of a circle with the natural boundary conditions.  We use a Morley element because the Swift-Hohenberg model contains 4-th order derivatives (the biharmonic operator). 

<img title="Swift-Hohenberg" alt="Alt text" src="/swift_ho_circle_mesh.png" width="350">

<br>
<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/square_react_dif.ipynb">
square_react_diff.ipynb: </a> Conventional periodic boundary conditions on a Cartesian grid integration of Reaction diffusion equations.

<br>
<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/square_swift_hohenberg.ipynb">
square_swift_hohenberg.ipynb: </a> Spectral method on a Cartesian grid integration of the Swift-Hohenberg equation. 

<br>
<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/fem_loop.ipynb"> fem_loop.ipynb: </a>
Wave and heat equation on a periodic 1d boundary with skfem

<br>
<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/fem_square_Laplace.ipynb"> fem_square_Laplace.ipynb</a> Solving Laplace's equation on the unit square with a mix of non-zero Neumann and Dirichlet boundary conditions. 

<br>
<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/fem_brus_circle_nonzeroneumann.ipynb"> fem_brus_circle_nonzeroneumann.ipynb </a>  Brusselator model with a non-zero Neuman boundary condition.  I also include an example with parts of the boundary satisfying Dirichlet and parts of the boundary satisfying Neumann conditions.  This uses skfem and a triangular mesh of the circle. 

<br>
<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/fem_GS_circle_nonzeroneumann.ipynb"> fem_GS_circle_nonzeroneumann.ipynb </a>
Gray scott model with a non-zero Neuman boundary condition.  I also include an example with parts of the boundary satisfying Dirichlet and parts of the boundary satisfying Neumann conditions.   This uses skfem and a triangular mesh of the circle. 
<br>
<a href="https://github.com/aquillen/Pattern_Formation_FEM/blob/main/fem_advec.ipynb"> fem_advec.ipynb </a>
Solving the advection diffusion equation with skfem on a triangular mesh of a circle. 

