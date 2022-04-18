# SelectTCR

## What does SelectTCR do?

`SelectTCR` was designed for selecting T cell receptors (TCRs) from 10X Genomics V(D)J sequencing for TCR retrogenic experiments. Retrogenic T cells express a chosen TCR that is induced through retroviral transfection. Unlike T-cell receptor transgenic mice, retrogenic TCRs can be rapidly generated (<6 weeks) for use both in vitro and in vivo and greatly expand opportunities for screening of TCRs identified in single cell experiments.

![SelectTCR](https://github.com/mattacottam/SelectTCR/blob/main/schem.jpeg?raw=true)

More information about generation of TCR retrogenic mouse can be found here: https://www.nature.com/articles/nprot.2006.61

`SelectTCR` provides a variety of functions for:

1. Integration of V(D)J data with `Seurat` objects
2. Storage of individual and paired TCR chain information
3. Exploration and identification of T cell clonotypes
4. Filters for quantification of TCR clonal enrichment across metadata features
5. Production of full length TCR sequences with inclusion of restriction sites and linker peptides (P2A & T2A)
6. Visualization of plasmid construct maps

## Installation

`SelectTCR` includes a wrapper function for `stitchr`. Installation instructions and more information about `stichr` can be found at https://github.com/JamieHeather/stitchr.

`SelectTCR` is currently under testing to ensure functionality across a variety of data sets. If you are looking for guidance on generating retrogenic T cell constructs and would like to share your data (or ideas) for testing, please send an email to `mattacottam@gmail.com`.
