<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Patch_of_the_New_York_City_Police_Department.svg/800px-Patch_of_the_New_York_City_Police_Department.svg.png" title="NYPD Logo" style="height:7em;float:right"/>
<h1 style="float:left;font-size:2.5em">NYC Motor Vehicle Crashes</h1>

*A Python exercise to preprocess a dataset about NYC Motor Vehicle Crashes.*

## Introduction

This repository contains a Jupyter notebook to help prepare a dataset to draw insights from regarding high-risk locations for vehicle crashes in New York City.

The source dataset is the [Motor Vehicle Collisions crash table](https://data.cityofnewyork.us/d/h9gi-nx95), and originates from [police reports (MV-104AN)](https://www.nhtsa.gov/sites/nhtsa.dot.gov/files/documents/ny_overlay_mv-104an_rev05_2004.pdf) filled in by the [NYPD](https://en.wikipedia.org/wiki/NYPD "New York City Police Department"). It is frequently updated and publicly available. To limit the initial scope, we will use a `.csv` file containing a subset of this data consisting of 100000 rows.

The desired output dataset is also a `.csv` file, cleaned as good as possible within the given time constraints, while adhering to the project requirements as listed below.

**Project requirements:**
* No missing values
* No duplicates
* Values are consolidated
* Correct data format
* No blank spaces

## Background information

The homepage of the dataset can be found [here](https://data.cityofnewyork.us/d/h9gi-nx95). For more personal notes, see the Jupyter notebook.

## Repository structure

* `data` folder contains input and output csv files
* the root folder contains the Jupyter notebook and this README file.

## Used software

Besides Python 3 and Jupyter notebook, please make sure you have the following installed:
1. `numpy` ([homepage](https://www.numpy.org/) | [installation instructions](https://numpy.org/install/))
1. `pandas` ([homepage](https://pandas.pydata.org/) | [installation instructions](https://pandas.pydata.org/docs/getting_started/install.html))
1. `pandas_profiling` ([github page](https://github.com/pandas-profiling/pandas-profiling) | [installation instructions](https://pandas-profiling.github.io/pandas-profiling/docs/master/rtd/pages/installation.html))

**Important:** *It's possible you need to activate the widgets extension for this notebook to work properly. See the [Jupyter section](https://pandas-profiling.github.io/pandas-profiling/docs/master/rtd/pages/installation.html#jupyter-notebook-lab) in the pandas_profiling installation instructions.*

## Further comments

This README file can undoubtedly be further improved, given more time.
Also, the Jupyter notebook contains more notes, and maybe some of them can be included here.
