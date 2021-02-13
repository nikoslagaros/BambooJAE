Changing the Geometry and the Setting of the structure in the algorithm you'll obtain the same analysis and optimization. 
Be sure that the points to be supported (using support command-Karamba 3D) are in the right position (global space). 
The type of load can be changed (example: from Mesh Load to Point load, Thermal Load, etc... - Uniform line ---> only beam element) from Load component (Karamba 3D).
The material and the cross-sections can be easily changed using a material selector or implementing a different one building the characteristics (as in the example .gh file). 
Octopus component (available on food4rhino) must work with SPEA Reduction with no more than 5 Obj. Fun. (set HypE Reduction if O.F.>5).