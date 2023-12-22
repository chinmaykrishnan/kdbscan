### TO-DO:
Add metrics (DB, silhoutte index) calculation.

This is an implementation of the paper [K-DBSCAN: An improved DBSCAN algorithm for big data](https://link.springer.com/article/10.1007/s11227-020-03524-3#citeas).

It containes two notebooks -

* kdbscan.ipynb - Clustering performed on the MAGIC telescope dataset

* kdbscan-abalone.ipynb - Clustering performed on the Abalone dataset

If you want to replicate the conda environment, the environment.yml file contains the dependencies. You can use ``conda env create -f path/to/environment.yml`` to create your own environment with the same configurations.