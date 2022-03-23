# stata_kernel

Minimal personal version.

Changes:
- Stata 17 inline graph fix from: https://github.com/simon-d-s/stata_kernel/tree/dev-stata17-graph-fix
- Added several Stata 16 and 17 commands to highlighting
- Updated Stata versioning in config and other files to 17
- Removed %help magic all together as it wasn't working properly (e.g., %help kernel was giving me an error)

To install in a conda environment:
```
conda install git
pip install git+https://github.com/gaksaray/stata_kernel@master
```

Tested on Anaconda version 2021.05 and Stata/SE 17.0 for Windows (64-bit).
