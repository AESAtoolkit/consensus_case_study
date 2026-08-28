# Overview
This repository provides the ``pyaesa`` implementation for generating AESA results for the consensus case study.\
It is made of two main folders:

1. the ``files`` folder gathers the files needed for MRIOs aggregation for the case study. These files will be automatically copied to the relevant location when running the main script in the ``scripts`` folder;

2. the ``scripts`` folder gathers (i) the main notebook generating results for a given functional unit, 
and (ii) another notebook to automatically run (i) for all functional units of interest in the context of the consensus. Running (ii) generates all the results of the case study.

# Packages installation

Before running the notebooks, make sure to install the necessary packages: 
- ``pyaesa`` (see more details below)
- see 'Imports' section in the notebooks.

# `pyaesa` installation

This notebook uses the `pyaesa` Python package (v1.2.8). Install the release from PyPI before running the workflow:

```bash
python -m pip install pyaesa
```

For package documentation, API reference, and tutorials, see [pyaesa.readthedocs.io](https://pyaesa.readthedocs.io/). 

The source code is available on GitHub at [AESAtoolkit/pyaesa](https://github.com/AESAtoolkit/pyaesa).

# Case study definition

The case study selected in the context of the AESA consensus is the electricity production in the Netherlands. 

