# miRNAgFree

miRNAgFree is a novel microRNA prediction approach based on biogenesis features, such as the known 5' fluctuation, and duplex mean free energies which does not require a genome assembly. We found that, in general, biogenesis related parameters are far more discriminative than duplex related structural parameters.

[Website](http://bioinfo2.ugr.es:8080/ceUGR/mirnagfree/)

[Standalone](http://bioinfo2.ugr.es:8080/ceUGR/wp-content/uploads/2017/08/miRNAgFree.zip)

[Manual](http://bioinfo2.ugr.es:8080/ceUGR/wp-content/uploads/2017/08/miRg_man25Sept.pdf)

© 2018 Computational Epigenomics Lab, Evolutionary Genomics and Bioinformatics Group. Dept. of Genetics, Inst. of Biotechnology, University of Granada, Spain

## Depencies
* [OpenJDK](http://openjdk.java.net) 1.8.0 or higher (64-bit) or [JRE](http://www.oracle.com/technetwork/java/javase/downloads) 8 or higher (64-bit).
* [RNAcofold](https://www.tbi.univie.ac.at/RNA/index.html#download) from Vienna Package 2.0 or higher (64-bit).

## Installation (standalone) (Debian/Ubuntu)
### OpenJDK
```
sudo apt-get install default-jdk
```
### Vienna Package
```
sudo apt-add-repository ppa:j-4/vienna-rna
sudo apt-get update
sudo apt-get install vienna-rna
```
