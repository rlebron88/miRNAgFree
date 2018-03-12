# miRNAgFree

miRNAgFree is a novel microRNA prediction approach based on biogenesis features, such as the known 5' fluctuation, and duplex mean free energies which does not require a genome assembly. We found that, in general, biogenesis related parameters are far more discriminative than duplex related structural parameters.

[Website](http://bioinfo2.ugr.es:8080/ceUGR/mirnagfree/)

[Standalone](http://bioinfo2.ugr.es:8080/ceUGR/wp-content/uploads/2017/08/miRNAgFree.zip)

[Manual](http://bioinfo2.ugr.es:8080/ceUGR/wp-content/uploads/2017/08/miRg_man25Sept.pdf)

## Dependencies
* [OpenJDK](http://openjdk.java.net) 1.8.0 or higher (64-bit) or [JRE](http://www.oracle.com/technetwork/java/javase/downloads) 8 or higher (64-bit).
* [RNAcofold](https://www.tbi.univie.ac.at/RNA/index.html#download) from Vienna Package 2.0 or higher (64-bit).

## Installation (Debian/Ubuntu)
### Standalone
```
sudo apt-get install unzip default-jre
sudo apt-add-repository ppa:j-4/vienna-rna
sudo apt-get update
sudo apt-get install vienna-rna
wget -c http://bioinfo2.ugr.es:8080/ceUGR/wp-content/uploads/2017/08/miRNAgFree.zip
unzip miRNAgFree.zip
```
### Source code
```
sudo apt-get install unzip git default-jre default-jdk
git clone https://github.com/mlhack/miRNAgFree.git
cd miRNAgFree
jar cvf miRNAgFree.jar libs/*.java miRNAgFree/*.java sequences/*.java 
```

## Quick Start
### Without install Vienna Package (standalone-only)
```
java –jar miRNAgFree.jar input=example_input.fa output=example_output_folder RNAcofold=./RNAcofold
```
### With Vienna Package already installed
```
java –jar miRNAgFree.jar input=example_input.fa output=example_output_folder
```

## Contact

This software was developped and is mantained by Michael Hackenber at University of Granada. Please contact him via [hackenberg@go.ugr.es](mailto:hackenberg@go.ugr.es). 

© 2018 Computational Epigenomics Lab, Evolutionary Genomics and Bioinformatics Group. Dept. of Genetics, Inst. of Biotechnology, University of Granada, Spain
