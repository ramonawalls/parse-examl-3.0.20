# parse-examl-3.0.20
Repository for creating docker container for parse-examl

From the ExaML manual:

"Use parse-examl to transform an alignment file in relaxed phylip format (as
used for RAxML) into a binary file format that can be read by ExaML. The main
reason for this is to allow ExaML to read this file faster and not waste any valuable
parallel computing time for this simple pre-processing task."

The Docker file uses code from https://github.com/stamatak/ExaML 

Please cite the following paper when using ExaML:

A. Kozlov, A.J. Aberer, A. Stamatakis: “ExaML Version 3: A Tool for
Phylogenomic Analyses on Supercomputer”. In Bioinformatics (2015)
doi: 10.1093/bioinformatics/btv184
