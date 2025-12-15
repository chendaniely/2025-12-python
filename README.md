# 2025-12-python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chendaniely/2025-12-python/master) <- click to rollow along without install

Install Python using Miniforge3: <https://github.com/conda-forge/miniforge>

We will be using the Jupyter Notebook (via jupyter lab).

You can install all the packages needed by opening up the **miniforge3 prompt** (windows) or terminal (mac).

```bash
conda install jupyterlab pandas scikit-learn seaborn plotnine
```

Getting the data:

1. If you know git, you can `clone` this repository.
2. If you do not know git, there is a green "Clone or download" button on the top of the page.
  You can click "Download ZIP" to download the contents of this project (including the datasets).

## Test your installation

If you can run the following lines in Python without error, you should be good to go

```python
import pandas as pd
import seaborn as sns
import sklearn as sk
```
