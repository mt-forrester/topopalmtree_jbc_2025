README file for Forrester et al, Topological Discovery of Transmembrane Protein S-Palmitoylation, J. Biol Chem 2025. PMID 39909380.

The folder contains 3 R markdown (.Rmd) files

1. transmembrane_palmitoylation_jbc_mar_2024.
This file contains all the R code related to feature extraction, model building and application.

2. visualizations_between_datasets.Rmd
Exploratory data analysis of the training data, validation (viral) dataset and other proteomes (mouse, human)

3. proteolysis_coverage_marc_2024.Rmd
Performs in silico digestion of TMP proteome. Relates to Figure 1 of main text.

The remaining csv's are either used as read-in files for Rmd file #1 (above) or are outputs of the gradient boosted tree model used to generate plots in Graphpad-Prism or for submission to GPS-Palm's windows interface.


Please note the following data files (.csv) are larger than GitHub's 100 MB limit and thus are not hosted here:

1. mouse_proteome_gbm_applied.csv (these are the results of the gradient boosted model applied to the mouse proteome, including all parameters and features). 

2. uniprot_mouse_total_membrane_proteome_gbm_applied_simple.csv. (these are the results of the gradient boosted model applied to the mouse proteome. These data are included as a supplementary table in the publication).

3. download_mammal_for_left_join.csv (UniprotKB-derived data necessary to merge topological information with SwissPalm-derived S-palmitoyl sites).

These csv files are available at my local drive:
https://drive.google.com/drive/folders/1b6ubRF_VRxX3MfUXYC8_uyZPqpOhRUWt?usp=drive_link