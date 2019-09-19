# Single-cell RNA-seq analysis best practices: Community Edition

This repository contains the best-practices for scRNA-seq analysis as determined by the 
community. Best practices are built upon the publication "Luecken and Theis, Current 
best practices in single-cell RNA-seq analysis: a tutorial, Mol Sys Biol (2019)".
Extensions to these best-practices are decided upon based on benchmarking results and 
discussion in this repo.

This project is currently still in the planning phase.


## Structure of the repository:

This repo contains 4 main sections:
1. benchmarks:

   A folder containing tool benchmarks in jupyter python notebooks. These benchmarks
   are discussed in PRs and github issues.

2. functions

   ScRNA-seq analysis tools that are considered (or have been considered as
   best practices. R tools are wrapped in rpy2 and anndata2ri function calls.

3. workflow scripts
   
   Scripts that use the best practices functions for data analysis case studies.


## Submission of best-practice candidates

To extend the current version of the best-practices with additional tools, we require:
1. An accepted benchmark that is published and/or pushed to the `benchmarks` folder.
   'Accepted' refers to benchmark studies that are follow the quality standards set out
   in this document.

2. A community discussion on this tool with final acceptance of the majority of parties
   involved and all core members of the best-practices team.


## TO DOs:

1. Determine standardized datasets for benchmarking
2. Determine benchmarking standards
3. Determine environment for benchmarking (docker container)
4. Write current best-practices pipeline into individual functions and reproduce the 
   notebook.
5. Decide upon scripts format: snakemake or jupyter notebook.



## Attribution:

### Planning:
Malte D Luecken  
Leander Dony  
Fabian Theis  

### Benchmarking:


### Code structure:
