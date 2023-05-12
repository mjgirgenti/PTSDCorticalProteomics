# PTSDCorticalProteomics

## System requirements
The codes are run on R (version 4.2.2) within Rstudio (version 2022.12.1 Build 353) on a Mac (macOS Venture 13.2.1). They should be run properly on R with version >= 4.0 and recent versions of Rstudio and operating systems.

## Installation guide
Installation of dependencies (R packages) may take up to a few hours depending on how many of them have been installed (most of them are commonly used R packages and can be found on R CRAN or Bioconductor).

## Demo
The R codes are designed for analyzing processed proteomics and miRNA data as inlcuded in `data` folder. Each R script is responsible for one or a few different tasks of analysis.
The expected output of `Proteomics_analysis.R` should be processed proteomics data, results of proteomics differential expression, WGCNA analysis and some other necessary analyses.
The expected output of `Proteomics_KDA_analysis.R` should be results of proteomics KDA analysis.
The expected output of `miRNA_analysis.R` should be processed miRNA data, results of miRNA differential expression, WGCNA and some other necessary analyses as well as those of enrichment analysis between proteomics and miRNA.
The expected output of `Figures_and_tables.R` should be main/supplementary figures and tables included in the manuscript (Wang et al. 2023).
Each section of R scripts may take seconds or up to tens of minutes of time.

## Instructions for use
The codes can be further extended to be applied on your own data if they follow the same data structures (proteomics or RNA-seq data with demographics information) and are properly cleaned or processed.

## Lisence
Apache Lisence 2.0
