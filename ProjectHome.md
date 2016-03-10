![http://gmsh2opensees.googlecode.com/files/splash.png](http://gmsh2opensees.googlecode.com/files/splash.png)

[Gmsh](http://geuz.org/gmsh/) is a general purpose finite element (FEM( 2D/3D mesh generator with post-processing capabilities and an intuitive GUI based interface. [OpenSEES](http://opensees.berkeley.edu), is an open-source finite element library with main emphasis in civil engineering applications. Gmsh lacks a FEM processor suitable for structural engineering needs and OpenSEES lacks a friendly interface.

Gmsh2OpenSEES (g2o), as it's name suggests, is a program written 100% in python which aims at bridging the gap between these two programs.

Currently, g20, reads gmsh's .msh (text) format importing nodes, element connectivity and physical group definitions. Additionally, it provides an interface to generate materials, assign element models, boundary conditions and other assigns.

The gap is only bridged one way.

Things to do.

  * Implement user variables
  * Implement implement patterns
  * Implement recorders
  * Implement analysis options
  * Implement reading recorder output and plotting
  * Implement recorder output to gmsh views