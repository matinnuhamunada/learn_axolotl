## Getting Started with Axolotl: BGC Analytics with PySpark and Bigslice
This tutorial is my personal getting started guide to utilizing [Axolotl](https://github.com/JGI-Bioinformatics/axolotl), a scalable distributed genome and metagenome data analysis for the exploration of genomic data, specifically focusing on the identification and study of BGCs, which are groups of genes involved in the biosynthesis of complex bioactive compounds.

### Installation

- Create the conda environment with:

```bash
mamba env create -f env.yaml
```

- Donwload BiG-SLICE HMM models
```
bash post-deploy.sh
```

### Running the notebook
To start the Jupyter notebook, run:

```bash
jupyter lab
```