# FVCA_Meshes
Archive of FVCA meshes and scripts to convert them into the [MED file format](https://docs.salome-platform.org/8/dev/MEDCoupling/med-file.html).
The [MED file format](https://docs.salome-platform.org/8/dev/MEDCoupling/med-file.html) is a binary format based on [HDF5](https://www.hdfgroup.org/solutions/hdf5/) used to store and manipulate large meshes.
The [MED library](ftp://ftp.cea.fr/pub/salome/prerequisites/med-4.1.1.tar.gz) can be downloaded [here](ftp://ftp.cea.fr/pub/salome/prerequisites/med-4.1.1.tar.gz) : ftp://ftp.cea.fr/pub/salome/prerequisites/med-4.1.1.tar.gz.  

- [**FVCA5**](https://www.i2m.univ-amu.fr/fvca5/) conference held in France in 2008 introduced a benchmark for the anisotropic diffusion equation on various 2D meshes (see [here](https://www.i2m.univ-amu.fr/fvca5/benchmark/bench.pdf) for the benchmark description).  
The FVCA5 meshes and their description can be found [here](https://github.com/wareHHOuse/fvca-meshes/tree/master/FVCA5) (meshes in bz2 compressed form) or on the original [website](https://www.i2m.univ-amu.fr/fvca5/benchmark/Meshes/index.html) in their original format. I uploaded the meshes in their original format [here](./FVCA5/OriginalMeshes).  
I converted the original meshes to the MED format unsing a [python script](./FVCA5/MEDFiles/convert_2Dmsh_to_med.py) and uploaded them [here](./FVCA5/MEDFiles).  

- [**FVCA6**](http://fvca6.fs.cvut.cz/) conference held in Prague in 2011 proposed a new benchmark for the diffusion equation on various 3D meshes this time.
The FVCA6 meshes in bz2 compressed form can be found [here](https://github.com/wareHHOuse/fvca-meshes/tree/master/FVCA6). The original meshes are no longer available on the website. I uploaded my old personal copy of the web site as well as MED file conversions.  

- [**FVCA8**](https://indico.math.cnrs.fr/event/1299/) conference held in France in 2017 introduced a new benchmark for the Navier-Stokes equations on various 2D and 3D meshes (see [here](https://github.com/FranckBoyer/FVCA8_Benchmark/blob/master/Benchmark.pdf) for the benchmark description).  
The FVCA8 meshes and their description can be found [here](https://github.com/FranckBoyer/FVCA8_Benchmark/tree/master/Meshes) in their original form. I uploaded MED file versions of all 2D and 3D meshes [here](FVCA8/MEDFiles).   

Some of the meshes used in these three conference benchmark are no longer available online. We regroup them in a single repository and propose python scripts to convert them into MED file format (see [here](https://www.salome-platform.org/user-section/about/med) for details of the MED format).  


