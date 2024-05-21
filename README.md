# EDL-BRKGA-Peptide-Design
- This repository presents a novel computational framework that integrates biophysics-based simulations (PepBD) with evidential deep learning (EDL) and metaheuristic search to accelerate the design of plastic-binding peptides.

- The framework leverages the predictive power of EDL to efficiently explore the vast peptide sequence space, while incorporating uncertainty quantification to prioritize promising candidates.

- Molecular dynamics simulations validate the efficacy of the designed peptides, demonstrating their superior binding affinity compared to existing solutions, thus opening a new avenue for bio-inspired microplastic remediation strategies.

## Citation
```
@article{https://doi.org/10.1002/aic.17469,
author = {Abdulelah S. Alshehri, Michael T. Bergman, Carol K. Hall, and Fengqi You},
title = {Biophysics-Informed Evidential Deep Learning for Uncertainty-Aware Design of Plastic-Binding Peptides},
journal = {},
volume = {},
number = {},
pages = {},
keywords = {},
doi = {},
url = {},
eprint = {,
abstract = {}

```
# About

## Overview
* `1 Data/` contains PepBD data results
* `2 Models/` contains EDL moddels
* `3 Codes/` contains peptide representation and genetic algorithm generation methods
* `4 Results/` contains the results of EDL and molecular dynamic simulations along with molecular dynamics comparisons between PepBD and EDL

## Requirements
* python (>=3.7)
* tensorflow (>=2.0)
* evidential-deep-learning
* Pickle
* functools
* pymoo

To install `evidential-deep-learning`: 
```
pip install evidential-deep-learning
```

To install `pymoo`: 
```
git clone https://github.com/anyoptimization/pymoo
cd pymoo
pip install .
```

## LICENSE: Attribution-NonCommercial 4.0 International 

