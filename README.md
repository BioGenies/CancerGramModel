[![R build status](https://github.com/BioGenies/CancerGramModel/workflows/R-CMD-check/badge.svg)](https://github.com/BioGenies/CancerGramModel/actions)

# CancerGramModel - Data and model storage for CancerGram

This package is used only as model and data storage for [CancerGram](https://github.com/BioGenies/CancerGram) - package 
for prediction of anticancer peptides using n-gram encoding and random forests.

The **CancerGram_model.rda** file stores the core functionality of CancerGram: the stacked random forest model
and list of informative n-grams used for classification of peptides/proteins as ACPs, AMPs or Negative.
It is essential for proper use of CancerGram but needs to be stored in the external repository due to large
size of the model and CRAN file size limit. 

