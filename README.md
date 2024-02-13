# SCLERA_Tutuila_Thermotolerance

This repository includes all data and code associated with the publication: 

Naugle MS, Oliver TA, Barshis DJ, Gates RD and Logan CA (2021) Variation in Coral Thermotolerance Across a Pollution Gradient Erodes as Coral Symbionts Shift to More Heat-Tolerant Genera. Front. Mar. Sci. 8:760891. doi: 10.3389/fmars.2021.760891

https://www.frontiersin.org/articles/10.3389/fmars.2021.760891/full 

The repository is organized in multiple parts:

## 1. Thermotolerance: 
Includes all CBASS acute heat stress assay measurements, as well as all predictive modeling. Here, you can find a script that reproduces **Tables 1-6** and **Figures 2 and 3** from the publication. 

## 2. Symbionts: 
Includes raw qPCR data, clean symbiont ratio data, and additional symbiont analyses not included in the publication. 

## 3. RNAseq: 
Includes pipeline to check QC, map to reference and create counts matrix in Bash. Also includes EdgeR scripts and WGCNA to examine baseline and heat stress gene expression modules. In the WGCNA folder within RNAseq, you may find the code to produce **Figures 4 and S6**. Raw reads may be found on the NCBI Sequence Read Archive (SRA) database (Bioproject accession: PRJNA762371; SRA accession: SRP339664). <https://www.ncbi.nlm.nih.gov/bioproject/762371>

## 4. LabProtocols:
Includes protocols for DNA and RNA extractions, cDNA library prep, and RNAlater homebrew recipe. 

## 5. Field HOBO Data:
Includes raw temperature data taken in 2019 in Tutuila. Also includes script and figure of plotted data. 

For questions or additional data/scripts, contact Melissa Naugle: <br>
melissasnaugle@gmail.com
