# stata_kernel

Minimal personal version.
- Stata 17 inline graph fix from: https://github.com/simon-d-s/stata_kernel/tree/dev-stata17-graph-fix
- Added several Stata 16 and 17 commands to highlighting
- Removed %help magic all together as it wasn't working properly (e.g., %help kernel was giving me an error)

To install in a conda environment:
```
conda install git
pip install git+git://github.com/gaksaray/stata_kernel@master
```
