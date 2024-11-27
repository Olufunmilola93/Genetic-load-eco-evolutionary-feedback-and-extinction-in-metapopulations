## Genetic load, eco-evolutionary feedback and extinction in metapopulations


### Project Abstract

Habitat fragmentation poses a significant threat to the persistence of populations, by generating increased genetic drift (and thus higher genetic load) as well as demographic stochasticity. Higher load causes population numbers to decline, which reduces the efficiency of selection and further increases load, resulting in a positive feedback which may drive entire populations to extinction. Here, we investigate this eco-evolutionary feedback in a metapopulation, focusing on how extinction thresholds depend on the total rate of deleterious mutations and their selection and dominance coefficients, the carrying capacity and growth rate of subpopulations, and the extent of migration between them. We first study the determinants of load under soft selection, where population sizes are constant, and then build upon this to analyse hard selection, where population sizes and load co-evolve. We show that in contrast to soft selection, high levels of migration are required to mitigate load and prevent extinction when selection is hard, with critical migration thresholds for metapopulation persistence increasing sharply with increasing ‘hardness’ of selection. Our analysis employs a combination of simulations and analytical approximations, allowing for a more comprehensive understanding of the factors influencing genetic load and extinction in fragmented landscapes.

<code style="color : blue"> This repository is the official implementation of the project described above.</code> 

### Layout

The repository is split into two main directories named Fortran and Mathemamtica. The Fortran directory houses codes run with Fortran and contains 7 subdirectories. Six of the subdirectories are named based on general parameter values used (for example, the directory named Ks10h002 contains results run with parameter values; per locus strength of selection scaled by the carrying capacity, $Ks = 10$ and dominannce coefficient, $h = 0.02$). The last subdirectory called $\textit{differentK}$ contains results run with different values  of carrying capacity, $K$. 

Within each subdirectory are .txt files named based on other specific parameters used and each .txt file contains several columms indicating computed statistics. Aside from the subdirectories, the Fortran directory also contains other fortran simulations (.f files) and their corresponding output (.txt) files. Again, in these cases, the name of the files indicate the parameters used for the run (e.g., sim_noLDL6000h002Km10.f indicates a simulation run assuming no LD (i.e., no linkage disequilibrium) with parameter values; number of loci, $L = 6000$, dominance coefficient, $h = 0.02$ and the strength of migration scaled by the carrying capacity, $Km = 10$). 


The Mathematica directory houses a mathematica notebook named Manuscript.nb which consists of the Mathematica codes for the analytical work done in the project. 

### Software versions

* Mathematica version 12.1 or later
* GNU Fortran 14.1.0

### Acknowledgements

This research was partially funded by the Austrian Science Fund (FWF) [FWF P-32896B] and DOC Fellowships of the Austrian Academy of Sciences: grants 26380 (O. Olusanya) and 26293 (K. Khudiakova).

We thank Prof. Nick Barton for useful comments on the project.
