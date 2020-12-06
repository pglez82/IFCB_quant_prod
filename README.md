# IFCB_quant_prod
## Introduction
We have to Jupyter Notebooks here. One is for finetuning the CNN, the other is for showing how to quantify. The former can be used as it is to fine tune the models to the plankton dataset. The latter should be replaced by a webservice that returns the quantification results for a given new sample.

### IFCB_FT
This finetunes a resnet to the plankton dataset. It saves everything to disk so it can be used by the quantification notebook.

### IFCB_quant
Uses the quantification library to compute the prevalence of each class in an unlabelled sample. 



