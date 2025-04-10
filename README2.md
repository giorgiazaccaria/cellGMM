# cellGMM

## Paper Information
**Title:**
Cellwise outlier detection in heterogeneous populations

**Authors:**
Giorgia Zaccaria, Luis A. García-Escudero, Francesca Greselin, Agustín Mayo-Íscar

**Github repository:**
https://github.com/giorgiazaccaria/cellGMM

## Information on this folder

**Description:**
This folder contains the codes for implementing the proposed methodology (cellGMM) and reproducing the analysis presented in Section 4.2 of the paper.

**Contents:**
- ** Codes for running cellGMM:** "cellGMM.R" (main script). 
   This script automatically calls the following files:  
    - "InitializationFunctions_cellGMM.R"; 
    - "InternalFunctions_cellGMM.R".
     
     *Usage:* 
     Open "cellGMM.R" from this folder or change your working directory in R/RStudio to this folder and run it.

- ** Code for reproducing the analysis in Section 4.2 of the paper and Figure 5:** "Tech-Fig5.Rmd". 
   This R Markdown file compares `cellGMM` with `cellMCD` and `DI`.   "Carina Nebula_Reduced.png" is uploaded.
    
    *Usage:* 
    Open "Tech-Fig5.Rmd" from this folder or change your working directory in RStudio to this folder and   
    run it.


