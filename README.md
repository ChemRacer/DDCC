# Data-Driven Coupled-Cluster

A repository containing code to run data-driven coupled-cluster singles and doubles (DDCCSD), as defined in references [1](https://pubs.acs.org/doi/10.1021/acs.jpclett.9b01442) and [2](https://pubs.acs.org/doi/10.1021/acs.jctc.0c00927). For ease of use, install the conda environment following the instructions in the repository [DDQC_Demo](https://github.com/ChemRacer/DDQC_Demo/tree/main). In that same repository, an example using the method from reference [1](https://pubs.acs.org/doi/10.1021/acs.jpclett.9b01442) can be found. In this repository, we have included a simple example for the method in reference [2](https://pubs.acs.org/doi/10.1021/acs.jctc.0c00927): `hydrocarbon_Pair_energy.ipynb`.


### Required Files
- `helper_CC_ML_spacial.py`
- `helper_ML_tools.py`
- `helper_ML_pairtools.py`


### Citations:
```
@article{townsend2019data,
  title={Data-driven acceleration of the coupled-cluster singles and doubles iterative solver},
  author={Townsend, Jacob and Vogiatzis, Konstantinos D},
  journal={The journal of physical chemistry letters},
  volume={10},
  number={14},
  pages={4129--4135},
  year={2019},
  publisher={ACS Publications}
}

@article{townsend2020transferable,
  title={Transferable MP2-based machine learning for accurate coupled-cluster energies},
  author={Townsend, Jacob and Vogiatzis, Konstantinos D},
  journal={Journal of Chemical Theory and Computation},
  volume={16},
  number={12},
  pages={7453--7461},
  year={2020},
  publisher={ACS Publications}
}
```

### References:
1. [Data-Driven Acceleration of the Coupled-Cluster Singles and Doubles Iterative Solver](https://pubs.acs.org/doi/10.1021/acs.jpclett.9b01442)
2. [Transferable MP2-Based Machine Learning for Accurate Coupled-Cluster Energies](https://pubs.acs.org/doi/10.1021/acs.jctc.0c00927)

