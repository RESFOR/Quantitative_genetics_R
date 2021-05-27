# quantitative_genetics_R

# multi-trait and milti-site ABLUP and HBLUP Copyright @ Dr. Eduardo Pablo Cappa (cappa.eduardo@inta.gob.ar)

# The multi-trait and milti-site R-script fits the standard pedigree-based ABLUP and combined pedigree-genomic based HBLUP models using the breedR R-package. The outputs of this R-script are the genetic and residual (co)variance components, and the breeding values and its accuracies for both models. 

# As an example, the RES-FOR lodgepole pine dataset (data_multi-trait_multi-site.txt) with 3 traits (DBH30, HT30, NSWGR36) and 4 sites (JUDY, VIRG, SWAN, and TIME) and the H-matrix calculated in blupf90 programs using the 8K ancestry selected SNPs.

# data_multi-trait_multi-site.txt is the demo dataset for the multi-trait and multi-site R script

# Spatial-competition-correction-mixed-model.R Copyright @ Dr. Eduardo Pablo Cappa (cappa.eduardo@inta.gob.ar)

# This R-script fit the standard, and the spatial (spline and autoregressive -AR1-) and/or competition individual-tree mixed models using the breedR R-package. Moreover, this R-script presents several modalities for diagnosing spatial and competition problems in forest genetic trials. Finally, the last lines of this R-script calculats the Design and Spatial phenotype adjustments. We also provide the total height at age 30 from the RESFOR spruce Red Earth (REDE) site as an example (data_spatial_competition_correction.txt).

# data_spatial_competition_correction.txt is the demo dataset for the Spatial-competition-correction-mixed-model.R

# AIM.coefficient.R performs SNP variable selection based on the AIM (ancestry informative marker, Rosenberg et al. 2003)

# AIM.coefficient.R copyright @ Blaise Ratcliffe (b.ratcliffe@gmail.com)
