# multigraph-colab


MultiGraph Generation Modules and Script Documentation
=====================================================

Module: multi_g_module.ipyn
---------------------------

This module contains functions and logic to generate a multigraph based on PDB files and activity values.


Script: multi_g_generation.ipyn
--------------------------------

This script imports the `multi_g_module` module to generate a multigraph based on PDB files and activity values.

Usage:
    - Ensure the `multi_g_module` module is in the same directory or is accessible in the Python path.
    - Data, including PDB files and activity values, should be placed in the 'MG/data' directory.


Data Location: 'MG/data'
------------------------

The 'MG/data' directory contains the following data:
    - PDB files: Molecular structure files in PDB format.
    - Activity values: Values associated with each PDB file, organized in csv file in 'MG/data/activity_data'.

Libraries Required:
-------------------

- math
- os
- itertools
- pandas
- numpy
- torch
- csv
- MDAnalysis
- Bio.PDB
- torch_geometric
- torch_geometric.data
- functools

Ensure that these libraries are installed before running the script.

