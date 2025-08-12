# opr_python

Utilities for making **CReSIS radar data** easy to load and work with in Python.  
Developed by **Nick Holschuh** (Amherst College) — nholschuh@amherst.edu.

## Overview

This package is intended to simplify the process of reading and plotting  CReSIS radar imagery in Python.  

## Install

You can install directly from Git (no PyPI publish required):

```bash
pip install "git+https://github.com/nholschuh/opr_python.git"
```

To pin a specific version/branch/commit:

```bash
pip install "git+https://github.com/nholschuh/opr_python.git@v0.1.0"
pip install "git+https://github.com/nholschuh/opr_python.git@main"
pip install "git+https://github.com/nholschuh/opr_python.git@abcdef1"
```

## Dependencies

- h5py==3.14.0
- hdf5storage==0.1.19
- mat73==0.65
- matplotlib
- numpy==2.3.2
- pyproj==3.6.1
- scipy==1.16.1

## Contributing

Issues and PRs welcome once the repository is public.  
Coding style: `black` (config in `pyproject.toml`).  
Tests: place under `tests/` and run `pytest`.

## Citation / Acknowledgments

- Data format and products by the **CReSIS** team. Please cite the appropriate CReSIS data DOIs when publishing results.
- Developed at **Amherst College** by **Nick Holschuh** (nholschuh@amherst.edu).

## License

