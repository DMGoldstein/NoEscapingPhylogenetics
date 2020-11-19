# Data and source code for the paper "There's no escaping phylogenetics" (Goldstein forthcoming)


## Overview

This repository contains the data and source code for the paper "There's no escaping phylogenetics," which will be published in a Festschrift.

## Data

The data used in the paper can be found in the folder `Data`, which contains three Nexus files: `Chang_kwe.nex` and `Chang_Augment.nex`. These contain the data for conjunctions that descend from \*/k^we/ and the augment.

## Code

The folder `Code` contains `.Rev` scripts for the two ancestral state estimation analyses. To run these files on your machine, you will need to supply a path for the object `data_path` in the first line of each script. 

## Trees

There are two files in the `Trees` folder, `ChangA3.tree` and `ieo_hundred.nex`. The first of these is the MAP tree from the A3 dataset and model of Chang et al. 2015 (which is configuration file `a1-c2-d0-g2-l2-s1-t1-z3` in their supplementary materials). The second is a sample of one hundred trees generated from this model and dataset. 
