# Overview of this repo

> This repo houses all of the code and analysis conducted for the manuscript "Variable gene expression and parasite load predict treatment outcome in cutaneous leishmaniasis". A link to the raw fastq file data hosted on GEO is provided [here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE127831). The abstract for the manuscript is copied below:

## Abstract
Patients infected with Leishmania braziliensis develop chronic lesions that often fail to respond to treatment. To determine whether genes whose expression is highly variable in lesions might influence disease outcome, we obtained biopsies of lesions from patients prior to drug treatment, performed transcriptomic profiling, and identified highly variable genes whose expression correlated with treatment outcome. Amongst the most variable genes were components of the cytolytic pathway, the expression of which appeared to be driven by parasite load in the skin. We demonstrated that treatment failure can be directly linked to the cytolytic pathway activated during infection. Using this host-pathogen biomarker profile, we show that treatment outcome can be predicted before the start of treatment. These findings not only raise the possibility of point-of-care diagnostic screening to identify patients at high risk of treatment failure and provide a rationale for a precision medicine approach to drug selection in cutaneous leishmaniasis, but more broadly also demonstrate the value of identifying genes of high variability in other diseases to better understand and predict diverse clinical outcomes.


> The locations of the core components of this repo are outlined in the file system map below. In short, there are the following main directories:

 - /ANALYSIS/code - contains the Rmarkdown (.rmd) file the combines all code and outputs and was used to generate the supplementary code file included in the manuscript the pipeline.  In addition, code for manuscript figures based on RNAseq data are included in this document.
 - /ANALYSIS/readmapping - includes Kallisto outputs and log files
 - /QA/fastqc - includes outputs from running [fastqc](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) on all raw fastq files.  Also contains a [multiqc](https://multiqc.info/) html summary report that summarizes fastqc and kallisto results.

```
