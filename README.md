# RNAseq_integr_visual
Functions to integrate RNAseq data with other data (e.g. clinical data) and visualize combined data

File descriptions:

Read_AE_SPPS_into_R.Rmd
This is an Rmd file that contains the import AE bit of my RNAseq pipeline. It does a few things:
- Imports Athero-Express data from an SPSS file
- Tidy the data, including setting the proper classes for the variables and switching value codes by value labels (easier for humans to read)

Variable_classes_AB.csv
This csv file contains the variable classes needed for the Read_AE_SPPS_into_R.Rmd file.
