# cellGMM

## Paper Information 
**Title:**
Cellwise outlier detection in heterogeneous populations

**Authors:**
Giorgia Zaccaria, Luis A. García-Escudero, Francesca Greselin, Agustín Mayo-Íscar

## Information on this repository
**Description:**
This folder contains the codes for implementing the proposed methodology (cellGMM) and reproducing the analyses presented in Sections 3 and 4.2 of the paper.

**Contents:**
- ** Codes for running cellGMM:** "cellGMM.R" (main script). 
   This script automatically calls the following files:  
    - "InitializationFunctions_cellGMM.R"; 
    - "InternalFunctions_cellGMM.R".
     
     *Usage:* 
     Open "cellGMM.R" from this folder or change your working directory in R/RStudio to this folder and run it.

- ** Code for reproducing Figures 1 and 2 of the paper:** "Tech-Figs1-2.Rmd". 
     This R Markdown file automatically uploads "Data-Figs1-2-Complete.RData", which containshe results of the analyses reported in Section3. 
     
     *Usage:* 
     Open "Tech-Figs1-2.Rmd" from this folder or change your working directory in R/RStudio to this folder and run it.
    
- ** Code for reproducing the analysis in Section 3 of the paper, Figures 1 and 2 and Table 1 for Scenario 1:** "Tech-Figs1-2-Tab1-Scenario1.Rmd". 
   This R Markdown file uses "snipEM_1.0.1.tar.gz" and "MixtureMissing_1.0.2.tar.gz" files if the user has not these packages already installed or a different version for *MixtureMissing*.
   
   *Usage:* 
     Open "Tech-Figs1-2-Tab1-Scenario1.Rmd" from this folder or change your working directory in R/RStudio to this folder and run it. **ATTENTION**: the user must have *Rtools* (for Windows) or *XCode* (for macOS), as well as the necessary tools for compiling and linking C/C++ code on the user's machine to install "snipEM_1.0.1.tar.gz" and "MixtureMissing_1.0.2.tar.gz".

- ** Code for reproducing the analysis in Section 4.2 of the paper and Figure 5:** "Tech-Fig5.Rmd". 
   This R Markdown file compares `cellGMM` with `cellMCD` and `DI`. "Carina Nebula_Reduced.png" is uploaded.
    
    *Usage:* 
    Open "Tech-Fig5.Rmd" from this folder or change your working directory in RStudio to this folder and run it.




