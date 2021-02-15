seaborn: statistical data visualization
=======================================

<div class="row">
<a href=http://seaborn.pydata.org/examples/anscombes_quartet.html>
<img src="http://seaborn.pydata.org/_static/anscombes_quartet_thumb.png" height="135" width="135">
</a>

<a href=http://seaborn.pydata.org/examples/multiple_regression.html>
<img src="http://seaborn.pydata.org/_static/multiple_regression_thumb.png" height="135" width="135">
</a>

<a href=http://seaborn.pydata.org/examples/many_facets.html>
<img src="http://seaborn.pydata.org/_static/many_facets_thumb.png" height="135" width="135">
</a>

<a href=http://seaborn.pydata.org/examples/structured_heatmap.html>
<img src="http://seaborn.pydata.org/_static/structured_heatmap_thumb.png" height="135" width="135">
</a>

<a href=http://seaborn.pydata.org/examples/scatterplot_matrix.html>
<img src="http://seaborn.pydata.org/_static/scatterplot_matrix_thumb.png" height="135" width="135">
</a>

<a href=http://seaborn.pydata.org/examples/horizontal_boxplot.html>
<img src="http://seaborn.pydata.org/_static/horizontal_boxplot_thumb.png" height="135" width="135">
</a>

</div>

--------------------------------------

[![PyPI Version](https://img.shields.io/pypi/v/seaborn.svg)](https://pypi.org/project/seaborn/)
[![License](https://img.shields.io/pypi/l/seaborn.svg)](https://github.com/mwaskom/seaborn/blob/master/LICENSE)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.883859.svg)](https://doi.org/10.5281/zenodo.883859)
[![Build Status](https://travis-ci.org/mwaskom/seaborn.svg?branch=master)](https://travis-ci.org/mwaskom/seaborn)
[![Code Coverage](https://codecov.io/gh/mwaskom/seaborn/branch/master/graph/badge.svg)](https://codecov.io/gh/mwaskom/seaborn)

Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics.


Documentation
-------------

Online documentation is available at [seaborn.pydata.org](https://seaborn.pydata.org).

The docs include a [tutorial](http://seaborn.pydata.org/tutorial.html), [example gallery](http://seaborn.pydata.org/examples/index.html), [API reference](http://seaborn.pydata.org/api.html), and other useful information.


Dependencies
------------

Seaborn supports Python 2.7 and 3.4+.

Installation requires [numpy](http://www.numpy.org/), [scipy](http://www.scipy.org/), [pandas](http://pandas.pydata.org/), and [matplotlib](http://matplotlib.org/). Some functions will optionally use [statsmodels](http://statsmodels.sourceforge.net/) if it is installed.


Installation
------------

The latest stable release (and older versions) can be installed from PyPI:

    pip install seaborn

You may instead want to use the development version from Github:

    pip install git+https://github.com/mwaskom/seaborn.git#egg=seaborn


Testing
-------

To test seaborn, run `make test` in the source directory.

This will exercise both the unit tests and docstring examples (using `pytest`).

 
Development
-----------

Seaborn development takes place on Github: https://github.com/mwaskom/seaborn

Please submit any reproducible bugs you encounter to the [issue tracker](https://github.com/mwaskom/seaborn/issues).

