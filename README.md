# Distributional Robustness via Invariant Gradients (DRIG)

This repository contains the code for the method *Distributional Robustness via Invariant Gradients (DRIG)* from the paper "[*Causality-oriented robustness: exploiting general additive interventions*]()" by Xinwei Shen, Peter Bühlmann, and Armeen Taeb (2023).

Below is a visual illustration of causality-oriented robustness a trade-off between in-distribution prediction and causality using our method DRIG that exploits general additive interventions in the data. DRIG encompasses anchor regression as a special case with mean shifts only. Our extended proposal DRIG-A provides a more flexible robustness framework.

![](causal_robust.pdf)


### Instructions

`estimate.py` contains functions to obatin various estimators, including DRIG, DRIG-A, observational and pooled OLS estimators, and anchor regression.

The notebooks correspond to the illustrative examples in the paper.
* `simu_pop_robust.ipynb`: Examples 1-2
* `simu_sample_robust.ipynb`: finite-sample version of Examples 1-2
* `simu_pop_adap_oracle.ipynb`: Example 3
* `simu_pop_adap.ipynb`: Example 4


### Contact information
If you meet any problems with the code, please submit an issue or contact [Xinwei Shen](mailto:xinwei.shen@stat.math.ethz.ch).