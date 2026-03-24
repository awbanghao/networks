This repository contains analysis scripts, data files, and output objects related to the NSHAP network analysis project conducted on March 24, 2026. 

File Descriptions:
1. Files_Script_240326.Rmd — Main R Markdown analysis script containing code, commentary, and procedures for data processing and network estimation.
2. Files_Script_240326.html — Knitted HTML version of the analysis script.
3. Files_Styles_240326.css — Custom stylesheet for formatting knitted HTML output.
4. Files_Codebook_140226.pdf — Codebook describing variables in the NSHAP dataset.
5. Files_Network_240326.pdf — Network plot visualisation generated from the analysis.
6. Output_BridgeValues_240326.csv — Bridge Expected Influence (BEI) values for all nodes.
7. Output_EdgeWeights_240326.csv — Estimated edge weights for all node pairs.
8. Output_Predictability_240326.csv — Nodewise predictability values.
9. Files_Dataset_240326.xlsx — Original NSHAP dataset.
10. Files_RawData_240326.RData — Raw dataset imported into R.
11. Files_ImputedData_240326.RData — Imputed dataset.
12. Files_Network_240326.RData — Final network object.
13. Files_Simulation_240326.RData — Network simulation object.
14. Files_BootstrapEdge_2402326.RData — Nonparametric bootstrap results for edge weights.
15. Files_BootstrapBEI_2402326.RData — Nonparametric bootstrap results for Bridge Expected Influence (BEI).
16. Files_BootstrapCaseDrop_2402326.RData — Case-dropping bootstrap results for BEI robustness analysis.

Usage:
1. Open Files_Script_240326.Rmd in RStudio.
2. Ensure all required .RData files are loaded into the working directory (same folder as analysis script).
3. Knit or run the R Markdown file to replicate the full analysis and generate visual outputs.
