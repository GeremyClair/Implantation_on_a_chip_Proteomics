# A microphysiological model of human trophoblast invasion during early embryo implantation
 Data analysis of the proteomics for the paper by Ju Young Park et al.

This repository contains the details of the proteomics data analysis for the paper  titled : “A microphysiological model of human trophoblast invasion during early embryo implantation“ by Ju Young Park and collaborators. The .raw data was deposited on MassIVE (https://massive.ucsd.edu/) under the identifier MSV000086888.

The data was pre-processed using MaxQuant (v1.6.0.16) using the default parameters except the following: trypsin was set as digestion enzyme, Label free quantification and iBAQ were active and match between run was enabled with a matching time window of 1.5 min. The “parameters.txt”, “peptide.txt”, “proteinGroups” and “summary.txt” from the MaxQuant txt folder are located in the subfolder named “01 - Source files” along with the associated metainformation on the samples.

The R markdown and the knitR html report are located in the main folder of the repository

All the files generated during the data analysis are located in the folder 03 - Output files.

Note that you can install [RomicsProcessor](https://github.com/PNNL-Comp-Mass-Spec/RomicsProcessor) on its dedicated repository.

Please let us know if you need any assistance in executing or understanding this code.
