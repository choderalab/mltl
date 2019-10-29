mltl
==============================
[//]: # (Badges)
[![Travis Build Status](https://travis-ci.org/REPLACE_WITH_OWNER_ACCOUNT/mltl.png)](https://travis-ci.org/REPLACE_WITH_OWNER_ACCOUNT/mltl)
[![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/REPLACE_WITH_APPVEYOR_LINK/branch/master?svg=true)](https://ci.appveyor.com/project/REPLACE_WITH_OWNER_ACCOUNT/mltl/branch/master)
[![codecov](https://codecov.io/gh/REPLACE_WITH_OWNER_ACCOUNT/mltl/branch/master/graph/badge.svg)](https://codecov.io/gh/REPLACE_WITH_OWNER_ACCOUNT/mltl/branch/master)

Machine learning of thermodynamic lengths.

### Contains

Dataset of relative hydration free energies and variances for pairs of molecules in the freesolv[Freesolv](https://github.com/MobleyLab/FreeSolv) dataset, for pairs of molecules with (0 or 1 unique old heavy atoms) and (0 or 1 unique new heavy atoms).

`generate-pairs.ipynb` searches through freesolv to find appropriate pairs, and analysis is performed in `analysis.ipynb`.

The intention is that it may be possible to _learn_ the variance of a simulation _a priori_ and use this for intelligent experiment design, using software such as [DiffNet](https://github.com/forcefield/DiffNet). 

### Useful References

(1) Mobley, D. L., and Guthrie, J. P., "FreeSolv: A database of experimental and calculated hydration free energies, with input files", Journal of Computer-Aided Molecular Design, 28(7):711-720 (2014) [Publication](https://pubs.acs.org/doi/abs/10.1021/ct800409d).
(2) Huafeng Xu, Optimal measurement network of pairwise differences, (2019). [Preprint](https://arxiv.org/abs/1906.08599).
### Copyright

Copyright (c) 2019, Chodera lab


#### Acknowledgements
 
Project based on the 
[Computational Molecular Science Python Cookiecutter](https://github.com/molssi/cookiecutter-cms) version 1.1.
