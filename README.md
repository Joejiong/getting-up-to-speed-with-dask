# Getting up to speed with Dask

<img alt="dask" src="https://docs.dask.org/en/latest/_images/dask_horizontal.svg" width="400">

[Dask](https://dask.org/) is a native Python library for parallel computing. This tutorial shows how you can scale data science from a laptop to a cluster using Dask.

## Notebooks

Create the conda environment and launch Jupyter Lab (or notebook).

```
conda env create -f environment.yml
conda activate dask-speed
jupyter lab
```

0. **Get data**: Pulls files from S3 
1. **Laptop**: Run analysis and train models using non-parallel Python packages. Try to load larger data, then run out of memory.
2. **Dask laptop**: Same analysis with larger data using Dask, still on laptop. Slow, but executes.
3. **Dask cluster**: Run analysis with a Dask cluster, super fast!

## Presentations

July 15, 2020 - ODSC Applied AI virtual event (recording pending)

- [Slides](odsc_slides.pdf)
- [Video](https://youtu.be/S_ncqocDcBA)

<iframe width="560" height="315" src="https://www.youtube.com/embed/S_ncqocDcBA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>