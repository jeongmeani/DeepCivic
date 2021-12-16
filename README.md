# Detect pathogenicity
Using ResNet network, predict pathogenicity from genetic data.

Original of this code was from Deeplearning lecture organized by "KoreaBio".
I have modified framework from Tensorflow to Pytorch and activation & loss fuction.


# Purpose
It is hard to discover whether this variant is pathogenic. Various information gotten from SVNbox that delivers genetic and peptide properties is useful to be feature.
And Clinvar provides pathogenicity of variants. Using this data and Resnet structure, have made AI model that predict pathogenicity. In the code with colab environment, check the data interpretation, manipulation and results.
