The Peaking Phenomenon in Semi-supervised Learning
=====
Authors: Jesse H. Krijthe and Marco Loog

This repository contains the code to generate/reproduce the paper "The Peaking Phenomenon in Semi-supervised Learning"

## Abstract
For the supervised least squares classifier, when the number of training objects is smaller than the dimensionality of the data, adding more data to the training set may first increase the error rate before decreasing it.  This, possibly counterintuitive, phenomenon is known as peaking. In this work, we observe that a similar but more pronounced version of this phenomenon also occurs in the semi-supervised setting, where instead of labeled objects, unlabeled objects are added to the training set. We explain why the learning curve has a more steep incline and a more gradual decline in this setting through simulation studies and by applying an approximation of the learning curve by Raudys & Duin.

## How to use this code
The easiest way to rerun the paper is by using knitr in RStudio to rebuild the peakingssl_spr.Rnw file. To rerun the experiments in the paper, see the code in the R directory.