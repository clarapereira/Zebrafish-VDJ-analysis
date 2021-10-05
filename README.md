# Zebrafish-VDJ-analysis

Code and tutorial for the analysis of V(D)J recombination in the zebrafish, using RNA-Seq data and the [MIXCR tool](https://mixcr.readthedocs.io/en/develop/). Here we provide the reference sequence of the zebrafish TRB locus, obtained from [REF], which, as of October 2nd, 2021 had not yet been deposited in the [IMGT](http://www.imgt.org/IMGTrepertoire/LocusGenes/locusdesc/zebrafish/TRD/Danrer_TRDdesc.html) database.  

#### 1. Install MIXCR and add zebrafish TRB sequences  

1.1. Follow the instructions of the developers as detailed [here](https://mixcr.readthedocs.io/en/develop/install.html).
1.2. Download the file provided here (add hyperlink to the json library) and save it in the `library` folder of the downloaded MIXCR tool, as detailed [here](https://mixcr.readthedocs.io/en/develop/importSegments.html#ref-importsegments). In short, as follows:  
>After mixcr installation, try, in the command line:
```sh
mixcr -v
```
Navigate to the folder specified in the command line (e.g., `/usr/local/Cellar/mixcr/3.0.13-2/libraries`), and save there the external library containing the reference TRB sequences.


#### 2. Clone `vdjveR` from Github  
`vdjveR` is an R package which contains functions that may help exploring VDJ diversity after alignment with MIXCR. One of the potentially useful functions is the calculation of equitability scores for the evaluation of the equivalence of the clones within a population.
> Clone `vdjveR` directly from the github repository:
```sh
```


#### 3. Prepare metadata table

#### 4. Perform the alignment  

#### 5. Extract productive and DJ alignments from mixcr output

#### 6. Merge all files in one table, add metadata
- export all, with metadata
- export productive clonotypes only
- export only productive TCR-B clonotypes

#### 7. Calculate Equitatibility
- plot data
