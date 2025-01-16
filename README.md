# Project in Molecular Life Science CB2050
## Evaluation of the linear discriminant analysis (LDA) model for tumor microenvironment characterization

### Overview
This repository contains the resources for analyzing breast cancer scRNA-seq and ISS transcriptomic data from the Janesick et al. (2023) study, created as part of the Project in Molecular Life Science (CB2050) course. It includes notebooks for preprocessing and analyzing scRNA-seq and ISS datasets, training LDA models, and performing differential gene expression (DGE) analysis.

### Data
- Chromium scRNA-seq data, including count matrix, feature, and barcode lists, are available in the following Google Drive folder: https://drive.google.com/drive/folders/14Y6csHwBJ_KGR7pPU6bO8sgFhsNSSfaT?usp=drive_link
- Xenium and Vizgen ISS datasets can be found here: https://drive.google.com/drive/folders/1KfcSJUEDn3UJxFnsixnLXUjWTvWy3Ymm?usp=drive_link
- Metadata is available here: https://drive.google.com/drive/folders/1XHkZ_wsk9y_LQwP4ydhZ5cj7kCtyat9v?usp=drive_link
- Necessary .rds files can be found here (or obtained from the analysis): https://drive.google.com/drive/folders/1UPB5Fgct1HTnDXq8rl1scaiNogfGN5aB?usp=drive_link

### Notebooks
- For scRNA-seq data handling, refer to the script in the scRNA-seq folder.
- For Xenium ISS data handling and scRNA-seq projections, refer to the script in the ISS folder.
- For various LDA applications, refer to the scripts in the LDA folder: LDA-17.rmd for cell type annotations for 17 cell types; Vizgen-script(LOG).rmd for cell type annotations for 3 cell types and TME annotations, validated on Vizgen data.
- For DGE analysis, refer to the script in the DGE folder. (Disclaimer: This script also includes LDA training on ISS TME labels and application to scRNA-seq data for TME annotations.)

### References
Janesick A, Shelansky R, Gottscho AD, Wagner F, Williams SR, Rouault M, et al. High resolution mapping of the tumor microenvironment using integrated single-cell, spatial and in situ analysis. Nat Commun. 2023;14(1). 
