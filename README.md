# RecoEcal-EgammaClusterProducers
This repository contains the weights to apply the DRN based energy regression correction to the Mustache superclusters reconstructed in the CMS ECAL 
 - models/MustacheEB and models/MustacheEE contain the weights and config for the EB and EE regressions. 
 - Each of those contains config.pbtxt with the triton configuration information and 1/model.pt with the model information and weights (ie this is the DRN compiled into torchscript) 
