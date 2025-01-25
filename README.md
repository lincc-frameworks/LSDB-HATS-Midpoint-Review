# LSDB Demo at the Midpoint Review 2025

Demonstration prepared for the MidPoint Review of LINCC Frameworks, Pittsburgh, 2025.
This demo showcases working with HATS-partitioned survey catalogs via [LSDB](https://lsdb.readthedocs.io/en/stable/).

### Main references

* [Slide deck](https://docs.google.com/presentation/d/1l0f3MMwpsQUn4JFcAKxlYRQ5eVZrlKJKtWheTq-lRXU/edit?usp=sharing))
* LSDB ([on GitHub](https://github.com/astronomy-commons/lsdb)) 
  ([on ReadTheDocs](https://lsdb.readthedocs.io/en/stable/))
* HATS ([on GitHub](https://github.com/astronomy-commons/hats))
  ([on ReadTheDocs](https://hats.readthedocs.io/en/stable/))
* nested-dask ([on GitHub](https://github.com/lincc-frameworks/nested-dask)) 
  ([on ReadTheDocs](https://nested-dask.readthedocs.io/en/stable/))
* nested-pandas ([on GitHub](https://github.com/lincc-frameworks/nested-pandas)) 
  ([on ReadTheDocs](https://nested-pandas.readthedocs.io/en/stable/))


## Getting Started 

You can follow along with this demo by creating your own local environment.

### Local installation

If installing in your own hardware, create a virtual environment and install the relevant packages:

```
>> conda create --name lincc python=3.12
>> conda activate lincc
>> pip install lsdb pyvo ipyaladin cesium scikit-learn aiohttp
```

## Notebooks

### [Notebook 1](Notebook_1_Load_and_Xmatch.ipynb)

In this notebook we will learn how to:

- Load object and source catalogs (lazily)
- Perform crossmatching with existing `LSDB` catalogs
- Save the results of a science workflow to disk

### [Notebook 2](Notebook_2_Basic_Time_Domain.ipynb)

In this notebook we will learn how to:

- Query and filter catalog data
- Compute time-series features for LSDB catalogs using `nested-dask`
- Plot light curves and periodograms

### [Notebook 3](Notebook_3_Vizier_LSDB_Interaction.ipynb)

In this notebook we will learn how to:

- Use VizieR TAP query to access tables and store/handle them in `LSDB`
- Use those catalogs to perform crossmatching with existing `LSDB` catalogs
- Perform time-series analysis and exploration with `nested-dask`

## LINCC Tech Talks

Watch the following [LINCC Tech Talk](https://www.youtube.com/watch?v=yoGhI72Vl40) to learn more about LSDB. Other relevant talks can be found in the [LSST Discovery Alliance website](https://lsstdiscoveryalliance.org/programs/tech-talks/).

## Acknowledgements

This project is supported by Schmidt Sciences.

This project is based upon work supported by the National Science Foundation under Grant No. AST-2003196.

This project acknowledges support from the DIRAC Institute in the Department of Astronomy at the University of Washington. The DIRAC Institute is supported through generous gifts from the Charles and Lisa Simonyi Fund for Arts and Sciences, and the Washington Research Foundation.
