## Genetic load, eco-evolutionary feedback and extinction in metapopulations
---

### Project Abstract
---

Fragmented landscapes pose a significant threat to the persistence of species as they are highly susceptible to heightened risk of extinction due to the combined effects of genetic and demographic factors such as genetic drift and demographic stochasticity. In this project, we explore the intricate interplay between genetic load and extinction risk within metapopulations with a focus on understanding the impact of eco-evolutionary feedback mechanisms. We distinguish between two models of selection: soft selection, characterised by subpopulations maintaining carrying capacity despite load, and hard selection, where load can significantly affect population size. Within the soft selection framework, we investigate the impact of gene flow on genetic load at a single locus, while also considering the effect of selection strength and dominance coefficient. We subsequently build on this to examine how gene flow influences both population size and load under hard selection as well as identify critical thresholds for metapopulation persistence. Our analysis employs the diffusion, semi-deterministic and effective migration approximations. Our findings reveal that under soft selection, even modest levels of migration can significantly alleviate the burden of load. In sharp contrast, with hard selection, a much higher degree of gene flow is required to mitigate load and prevent the collapse of the metapopulation. Overall, this study sheds light into the crucial role migration plays in shaping the dynamics of genetic load and extinction risk in fragmented landscapes, offering valuable insights for conservation strategies and the preservation of diversity in a changing world.


<code style="color : blue"> This repository is the official implementation of the project described above.</code> 


### Layout

The repository is split into two main directories named Fortran and Mathemamtica. The Fortran directory houses codes run with Fortran and contains 7 subdirectories. Six of the subdirectories are named based on general parameter values used (for example, the directory named Ks10h002 contains results run with parameter values; per locus strength of selection scaled by the carrying capacity, $Ks = 10$ and dominannce coefficient, $h = 0.02$). The last subdirectory called $\textit{differentK}$ contains results run with different values  of carrying capacity, $K$. 

Within each subdirectory are .txt files named based on other specific parameters used and each .txt file contains several columms indicating computed statistics. Aside from the subdirectories, the Fortran directory also contains other fortran simulations (.f files) and their corresponding output (.txt) files. Again, in these cases, the name of the files indicate the parameters used for the run (e.g., sim_noLDL6000h002Km10.f indicates a simulation run assuming no LD (i.e., no linkage disequilibrium) with parameter values; number of loci, $L = 6000$, dominance coefficient, $h = 0.02$ and the strength of migration scaled by the carrying capacity, $Km = 10$). 

The Fortran codes were written by coauthor Himani Sachdeva (himani.sachdeva@univie.ac.at).


The Mathematica directory houses a mathematica notebook named Manuscript.nb which consists of the Mathematica codes for the analytical work done in the project. The Mathematica code was written by Olusanya Oluwafunmilola (funmilola@aims.ac.za).



### Project Authors

* Oluwafunmilola Olusanya (funmilola@aims.ac.za)
* Ksenia Khudiakova, Institute of Science and Technology, Austria (kseniia.khudiakova@ist.ac.at)
* Himani Sachdeva, Department of Mathematics, University of Vienna, Vienna 1090, Austria (himani.sachdeva@univie.ac.at)


