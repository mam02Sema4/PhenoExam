# PhenoExam

## How to install PhenoExam package

~~~
# If you don't have devtools package
install.packages("devtools")
library(devtools)

# Install PhenoExam package 
install_github("alexcis95/PhenoExam")
library(PhenoExam)
~~~

You need the following bioconductor packages:  

clusterProfiler  
AnnotationDbi  
org.Hs.eg.db  

~~~
# How to install Bioconductor Packages
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("org.Hs.eg.db")
~~~

You need the following R packages:  

readr  
data.table  
ggplot2  
stats  
plotly  
ggpubr  
dplyr  
viridis 
parallel  
purrr  
DT  
Hmisc  
pheatmap  


## Uses of PhenoExam


**PhenoExam** is an R package that performs (1) phenotype enrichment analysis on a gene set, (2) measures statistically significant phenotype similarities between gene sets and (3) detects significant differential phenotypes for them. Phenotypic Similarity between two groups of genes is performed by assessing the statistical significance of the Phenotypic Overlap Ratio (POR) between those (i.e. the number of common relevant phenotypes between the gene sets). PhenoExam uses the HPO, MGD, and CRISPRbrain databases for phenotypes. PhenoExamWeb uses UNIPROT, CTD, ORPHANET, CLINGE, GENOMICS ENGLAND, CGI and PSYGENET to obtain diseases terms through DisGeNET database.   


# Available tutorials

[Phenotype analysis tutorial](https://rawcdn.githack.com/alexcis95/PhenoExamWebTutorials/d089fa3530033cfc26d69dce055d04bbcfc14087/tutorial.html)


# PhenoExamWeb Shiny app  

[PhenoExamWeb shiny app](https://snca.atica.um.es/PhenoExamWeb/)

# About  


This work is the result of a pre-doctoral training contract for research staff financed by the CARM Ministry of Employment, Research and Universities, through the Seneca Foundation - Science and Technology Agency of the Region of Murcia. This package has developed by **Alejandro Cisterna García** as part of his PhD mentored by professor **Juan Antonio Botía Blaya**.  


Authors:
Alejandro Cisterna, Aurora González, Daniel Ruiz, Jordi Ortiz, Irene Díez, Paolo Maietta, Sara Álvarez, Mina Ryten, Juan A. Botía  


