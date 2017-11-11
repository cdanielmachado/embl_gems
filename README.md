[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

# EMBL GEMs

## A collection of GEnome-scale Models for bacterial species

This is a collection of genome-scale models built for all reference and representative bacterial genomes of NCBI RefSeq (release 84) using [CarveMe](https://github.com/cdanielmachado/carveme). It currently contains 5587 models which represent the metabolic diversity across bacterial life at the strain level. 

You can search any bacterial strain by name or by the respective RefSeq assembly accession code. This database is organized as follows (**x** is the first letter of the genus):

```models/x/genus/species_strain (assembly accession)```

Note: the files are stored in compressed SBML format (which can be directly imported by libSBML). Initial conditions (i.e. medium composition) are not pre-defined. To obtain biologically meaningful simulation results, it is recommended to define the desired conditions accordingly.