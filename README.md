Python notebooks that illustrate some pattern formation models (mostly on triangular meshes and without periodic boundaries).

fem_brus_circle.ipynb : Brusselator reaction diffusion equation on a triangular mesh of a circle.  The boundary condition is Neumann with both fields having normal component of gradient equal to zero. The system is integrated with the scikit-fem finite element package. 

fem_complex_ginzburg_landau.ipynb:  Integrating the Complex Ginzburg Landau equation on a triangular mesh of a circle with the Neumann boundary condition. 

fem_swift_hohenberg.ipynb:  Integrating the Swift-Hohenberg model on a triangular mesh of a circle with the natural boundary conditions.  We use a Morley element because the Swift-Hohenberg model contains 4-th order derivatives (the biharmonic operator). 
<img title="Swift-Hohenberg" alt="Alt text" src="/swift_ho_circle_mesh.png" width="350">

square_react_diff.ipynb:  Conventional periodic boundary conditions on a Cartesian grid integration of Reaction diffusion equations.

square_swift_hohenberg.ipynb:  Spectral method on a Cartesian grid integration of the Swift-Hohenberg equation. 



