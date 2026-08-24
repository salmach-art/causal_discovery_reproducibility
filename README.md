# causal_discovery_reproducibility
Code and datasets accompanying the paper "Causal Bayesian Network Learning: Bridging Observational Learning and Expert Knowledge"

# Reproducibility Materials — CBN Causal Discovery Study

The original experiments were conducted in Python using Anaconda and Jupyter
Notebook. This repository provides a part of documented implementation of the experimental procedures.

## Reference sources
- Asia_data: publicly available benchmark observational dataset.
- Elderly_data: real-world clinical dataset; complete data are restricted.
- Suicide_CBN: expert-defined CBN; observational data were generated synthetically.

## Experiments
- semi-synthetic generation for Asia/Elderly;
- fully synthetic generation for Suicide;
- sample sizes 500, 1,000, 5,000, 10,000 and 50,000;
- latent-confounder experiment using causal-learn FCI;
- default vs retrospectively selected best configurations;
- expert required/forbidden constraints;
- SHD, nSHD and edge metrics.

## Notebooks
01_CBN_and_CPT_definition
02_Synthetic_Data_Generation
03_Varying_Sample_Sizes
04_Causal_Discovery_Experiments
05_Latent_Confounders_FCI
06_Expert_Constraints
07_Evaluation_Metrics

## Data sharing
The complete Elderly clinical dataset should not be uploaded unless authorized.
The exact CBN/CPT files should likewise be shared only when redistribution is permitted.

