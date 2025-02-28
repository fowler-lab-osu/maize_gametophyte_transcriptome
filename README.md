# Transcriptome paper R methods
Cedar Warman, Sam Hokin, Duo Jiang

## Overview
This git repository contains the code (organized in an RStudio project) used to analyse a portion of the data produced in the study "Highly expressed maize pollen genes display coordinated expression with neighboring transposable elements and contribute to pollen fitness," as well as to generate plots for the majority of the figures.

## How to run
First, open the Transcriptome_paper_git_version.Rproj. This project contains R scripts that cover the various analyses performed in the paper. R scripts can be run in any order, as data used for each script (for example the data used for plotting) has been generated and saved in the ./data/raw_data directory. These data can be regenerated by running their associated scripts.

## Contents
### transcriptome_summary_plots.R
This script contains the code used to generate the PCA plot in Figure 1B, as well as the Venn diagrame in Figure 4B.

### functional_validation_of_transcriptome_data.R
This script contains the analysis performed in the "Large-scale insertional mutagenesis supports a relationship between transcript level and fitness contribution for vegetative cell-expressed genes" section of the paper. It includes generalized linear models for each expression category (Seedling, Vegetative Cell, Sperm Cell), proportion tests comparing the categories, Vegetative Cell category regressions comparing expression to transmission rates, and an analysis of the presence of Ac in a subset of lines. In addition, it contains the code used to generate the plots in Figure 6.

### gex2_phenotyping.R
This script contains the code used to analyze to gex2 phenotypes, including small seed counts and empty ear area. It also contains the code used to generate the plots in Figures 7E and S5.