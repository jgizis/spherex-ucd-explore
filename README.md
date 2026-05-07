# spherex-ucd-explore
explore using the SPIFF spectra extracted from SphereX data 

The SPIFF data are from Gagne et al. https://arxiv.org/html/2604.22012v1#S4

Zenodo https://zenodo.org/records/19051216

read_spiff is notebook to read the original Zenodo files

MANUAL_EDITS.txt is a record of some minor edits to the original Zenodo files

spiff_known_pca is notebook with simple Principal Components Analysis PCA

We also compare to models

rebin_diamondback
rebin_ATMO2020

rebins the model synthetic spectra as distributed by original authors to
   match SPIFF

and then
read_diamondback
etc. reads these files and makes a 2-D array, pickle just like SPIFF Data

applt_PCA_to_models
uses the PCA analysis on the actual data to plot the models



