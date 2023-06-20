# GFLV-RNA-Seq

This Github is designed for transparent analysis of data presented in Roy et al. 2023. 
https://pubs.acs.org/doi/full/10.1021/acs.jproteome.3c00069 

All console scripts, R markdown code, and other data manipulation should be up to date and properly annotated within this repository for data associated with Bioproject PRJNA838211.

If there are any discrepancies or questions, please make a fork or comment on this repository or email the corresponding author of the manuscript.

The code is split into four main analyses with the respective file dependencies listed underneath: 

(1) Viral RNA-Seq & LC-MS/MS Analysis

    "Viral_Sample_metadata.txt", "viralgeneCount.txt", "Viral Reads Table.csv", "viralprotein.csv"
    
(2) Host RNA-Seq Analysis

    "geneCount.txt", "Sample_metadata.txt", "fourdaycoldata.csv", "sevendaycoldata.csv", "twelvedaycoldata.csv"
    
(3) Gene probing of host RNA

    Run (2) Host RNA-Seq Analysis Rmd

(4) WGCNA and enrichment analysis

    Run (2) Host RNA-Seq Analysis Rmd
