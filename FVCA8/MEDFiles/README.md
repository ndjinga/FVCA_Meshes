# Conversion of the meshes of the FVCA8 benchmark 
The 2D mesh families were not available in .msh format and were regenerated from scratch in [med format](https://docs.salome-platform.org/8/dev/MEDCoupling/med-file.html) using a python script given in each folder.  

The 3D mesh families were available in the .msh format. We therefore opened them with the software [GMSH](http://gmsh.info/doc/texinfo/gmsh.html#MSH-ASCII-file-format) and exported them in the MED (.med) format.

