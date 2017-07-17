# Jupyter with Python

If you are unfamiliar with the Jupyter notebook environment, or with Python, the following steps will help you get started: 

1. \[Start an iPython notebook\]

2. The Python distribution included in this sandbox is version 3.6.1, and includes the <a href="https://docs.python.org/3/library/" target="_blank"> Python standard code library</a>).

3. You will need additional packages to carry out common data science operations. We suggest you begin by installing <a href="http://www.numpy.org/" target="_blank"> NumPy</a>, <a href="https://www.scipy.org/scipylib/index.html" target="_blank">SciPy</a>, <a href="http://matplotlib.org/" target="blank">matplotlib</a> and <a href="http://pandas.pydata.org/" target="_blank">pandas</a> as follows:

```
import numpy as np
import scipy as sp
import matplotlib as mpl
import pandas as pd
```

Additional Python packages are available <a href="https://pypi.python.org/pypi" target="_blank">here</a>).
There are many popular Python tutorials and courses available online, which will help you get familiar with the language. Examples include:

* [The Python tutorial by the Python Software Foundation](https://docs.python.org/3/tutorial/)
* [Python courses offered through Coursera](https://www.coursera.org/courses?languages=en&query=python)
* \[insert others\]

## Read data

To read data from a .csv file into a Python dataframe, do the following:

```
df = pd.read_csv('.../filepath.csv')
```

where ``filepath`` refers to the location of your data.

This creates a dataframe \(defined as df\) containing the data from your file.

You are now ready to start analysing your data.

## Data analysis

There are many popular tutorials and courses available online, which will help you analyse your data using Python. Examples include:

* [Intro to Python for Data Science by DataCamp](https://www.datacamp.com/courses/intro-to-python-for-data-science)
* \[insert others]

## Edit sandbox configuration

In the \[root?\] of your Jupyter environment, click on the tab called ``conda``.
This shows you which packages are already installed \(right hand side box\), and which new ones you can add \(left hand side box\) as follows:

![screenshot showing Jupyter conda](/documentation/figures/jupyter-conda.png)

Select the packages you wish to add, and click on ``update selected packages`` \(cloud icon with arrow\).

## Share your work

The easiest, most effective way to share your work is by using GitHub.

1. \[insert steps to creating GitHub account and/or linking to sandbox login\]
2. \[decide on whether you can share your code in a public repo, or need to keep it private \]\[link to principles on public vs private\]
3. \[commit ``.ipynb`` file to new repo\]