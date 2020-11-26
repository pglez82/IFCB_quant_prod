# IFCB_quant_prod
## Introduction
Here we need the following things:
1. Function `prepareImages` in order to proper resize all the images (so they are sutable for the neural network).
2. Function `computeDeepFeatures`that will compute all the deep features for a directory of images (using a model).
3. Once we have the deep features we need the quantification library. We have to take into account that we need to train a model so we have another option here.

Idea: use pytorch to finetune a resnet (we already have it done). Just quantify using the outputs of the resnet and passing it to the quantification lib. That should be quite easy overall and cleaner.



