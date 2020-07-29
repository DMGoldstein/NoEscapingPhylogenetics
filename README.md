# Data and source code for the paper "There's no escaping phylogenetics"


## Overview

This repository contains the data and source code for the paper "There's no escaping phylogenetics," which will be published in a Festschrift.

## Data

The data used in the paper can be found in the folder `Data`, which contains three Nexus files: `Chang_Augment.nex`, `Chang_Def_Multi.nex`, and `Chang_postposed_conjunction.nex`. These contain the data for the augment, the definite article, and postposed conjunction. 

## Code

The folder `Code` contains `.Rev` scripts for each of the ancestral state estimation analyses. To run these files on your machine, you will need to supply a path for the object `data_path` in the first line of each script. 

## Trees

There are two files in the `Trees` folder, `ChangA3.tree` and `ieo_fifty.nex`. The first of these is the MAP tree from the A3 dataset and model of Chang et al. 2015 (which is configuration file `a1-c2-d0-g2-l2-s1-t1-z3` in their supplementary materials). The second is a sample of fifty trees generated from this model and dataset. 
