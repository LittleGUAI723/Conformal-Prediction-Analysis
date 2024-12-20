# Batch Multivalid Conformal Prediction

This repository contains code for the paper *Batch Multivalid Conformal Prediction* by Christopher Jung, Georgy Noarov, Ramya Ramalingam, and Aaron Roth.

The `src/` folder contains Python implementations for our multivalid conformal predictors, along with other utilities such as plotting tools and conformal scorers. 
In particular:

1. The algorithm `BatchMVP` is implemented in `/src/MultivalidAlgorithms/MultivalidCoverage.py`
2. The algorithm `BatchGCP` is implemented in `/src/MultivalidAlgorithms/GroupCoverage.py`

The `experiments/` folder contains Jupyter notebooks implementing the experiments in the paper.

You may find the dataset at https://drive.google.com/drive/folders/1_TNoMangVLbvNQP360Ut8pEv_SdFvHnI?usp=share_link
