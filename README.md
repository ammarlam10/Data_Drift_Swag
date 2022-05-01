# SWAG for Data Drift

This repository contains a PyTorch implementation of Stochastic Weight Averaging-Gaussian (SWAG) from the paper

[A Simple Baseline for Bayesian Uncertainty in Deep Learning](https://arxiv.org/abs/1902.02476)

by Wesley Maddox, Timur Garipov, Pavel Izmailov, Dmitry Vetrov, and Andrew Gordon Wilson

## How to run
mvtec_swag notebook acesses all other resources in the repository. To run SWAG training, run mvtec_swag notebook which will generate a checkpoints\swag-20 or checkpoints\swag-40 file based on the epochs used.

use the generated SWAG file in 'entorpy calculation' notebook to get entropies of in-class and drifted data

Finally, use entropy plots to create entropy hisograms.
## References for Code Base

Stochastic weight averaging gaussian: [Pytorch repo](https://github.com/wjmaddox/swa_gaussian). 
