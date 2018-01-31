[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

![EMBL GEMs](logo_300px.png)

## A collection of GEnome-scale Models for bacterial species

This is a collection of genome-scale models built for all reference and representative bacterial genomes of NCBI RefSeq (release 84) using [CarveMe](https://github.com/cdanielmachado/carveme).

It currently contains 5587 models which represent metabolic diversity across bacterial life at the strain level. 

The database is organized as follows (**x** is the first letter of the genus):

```models/[x]/[genus]/[species]_[strain].xml.gz```

You can also search organisms by their taxonomic id or RefSeq assembly accession code in the master table: `model_list.tsv`. 


#### Notes:

* The files are stored in compressed SBML format, which can be directly imported by any simulation tool that uses libSBML (we recommend [framed](https://github.com/cdanielmachado/framed) or [cobrapy](https://github.com/opencobra/cobrapy) for simulation purposes). 

* Specific media compositions are not defined in the models (i.e. all exchange reactions are simply open by default). To obtain biologically meaningful simulations we recommend that you define suitable experimental conditions accordingly.