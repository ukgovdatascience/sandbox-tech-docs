# Jupyter with Python

If you are unfamiliar with the Jupyter notebook environment, or with Python, the following steps will help you get started: 

1. \[Start an iPython notebook\]

2. The Python distribution included in this sandbox is version 3.6.1, and includes the [Python standard code library](https://docs.python.org/3/library/).

3. You will need additional packages to carry out common data science operations. We suggest you begin by installing [NumPy](http://www.numpy.org/), [SciPy](https://www.scipy.org/scipylib/index.html), [matplotlib](http://matplotlib.org/) and [pandas](http://pandas.pydata.org/) as follows:

```
import numpy as np
import scipy as sp
import matplotlib as mpl
import pandas as pd
```

Additional Python packages are available [here](https://pypi.python.org/pypi).

## Upload data

To read data from a .csv file into a Python dataframe, do the following:

```
df = pd.read_csv('.../filepath.csv')
```

where ``filepath`` refers to the location of your data.

This creates a dataframe \(defined as df\) containing the data from your file.

You are now ready to start analysing your data.

## Data analysis

There are many popular Python tutorials and courses available online, which will help you analyse your data. Examples include:

\[insert]