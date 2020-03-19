# 440_project
## Overview

This repository contains the data, code, and figures that will be generated for studying BV-associated bacterial species, relationships, and vaginal microbiome compositions across ethnic groups. This analysis is being performed for the term project of course 20.440 of Spring 2020. The specific aims of the project are listed below.

### Specific Aims
Specific Aim 1. To study diversity, Shannon diversity indices will be calculated for all samples and clustering methods will be used to find microbiome composition types within ethnic groups. Correlations between BV phenotypes (Nugent scores, Amsel criteria, pH, other metadata) and diversity scoring and composition types will be tested and compared across ethnic groups.

Specific Aim 2. To study microbial interactions, positive and negative correlations between microbe genus and species will be calculated within and compared across ethnic groups. The presence of either a strong positive or negative correlation will also then be correlated with BV phenotypes. 

Specific Aim 3. Species diversity within the Lactobacilli genus will be calculated for each ethnic group and correlated with BV phenotypes.

## Data
To conduct This computational analysis, public datasets from Ravel et al and Srinivasan will be used to support these analyses. Both datasets provide metagenomic sequencing information for vaginal samples collected from women with and without BV and relevant patient metadata. Both studies prioritized collecting patient metadata such as pH and Nugent scores, which can be used to assess risk for or diagnose BV. Additionally, Srinivasan et al’s dataset provides metadata on the women’s menses status, amsel criteria (also used to diagnose BV), vaginal fluid normality, presence of clue cells, and whiff test results.

### References
(1) 	Alcendor, D. J. Evaluation of Health Disparity in Bacterial Vaginosis and the Implications for HIV‐1 Acquisition in African American Women. Am. J. Reprod. Immunol. 2016, 76 (2), 99–107. https://doi.org/10.1111/aji.12497.

(2) 	Srinivasan, S.; Hoffman, N. G.; Morgan, M. T.; Matsen, F. A.; Fiedler, T. L.; Hall, R. W.; Ross, F. J.; McCoy, C. O.; Bumgarner, R.; Marrazzo, J. M.; Fredricks, D. N. Bacterial Communities in Women with Bacterial Vaginosis: High Resolution Phylogenetic Analyses Reveal Relationships of Microbiota to Clinical Criteria. PLoS ONE 2012, 7 (6). https://doi.org/10.1371/journal.pone.0037818.

(3) 	Ravel, J.; Gajer, P.; Abdo, Z.; Schneider, G. M.; Koenig, S. S. K.; McCulle, S. L.; Karlebach, S.; Gorle, R.; Russell, J.; Tacket, C. O.; Brotman, R. M.; Davis, C. C.; Ault, K.; Peralta, L.; Forney, L. J. Vaginal Microbiome of Reproductive-Age Women. Proc. Natl. Acad. Sci. 2011, 108 (Supplement 1), 4680–4687. https://doi.org/10.1073/pnas.1002611107.

## Folder Structure
This repository contains this README.md file and the following folders: code, data, and fig. All python scripts for performing analyses on the data and generating figures can be found in the code folder. The data folder contains a raw and processed subfolder. All data used from the Ravel et al and Srinivasan et al studies can be found in the data/raw. All processed data files generate using any scripts can be found in data/processed/[date of analysis_foldername]. All figures generated fig/[date of analysis_foldername].

## Installation
To run "20200318_data_visual_init", please download this entire repository including all subfolders. This script runs on python 3 and requires python packages which can be found in the script under #BASIC IMPORTS. If not already, please install those packages using pip or conda install in your terminal. After downloading the repo and installing packages, the file_path and output file paths should be changed in the "20200318_data_visual_init.py" script. The file_path is the file path for reading in the raw data, and the output file paths are for where to save processed data and figures.
