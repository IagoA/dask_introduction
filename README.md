# Introduction to Dask

This code repository is part of the introduction to distributed computing with Dask session.

## Installation

### Environment installation

It is recommended to create a specific virtual environment for the repository.
To be able to manage dependencies and Python version at the same time in a simple way, it is recommended to use [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

Open a terminal at the root of the repository and create a new python environment.

```shell
conda create -n dask_introduction python=3.12
```

Then, it is necessary to activate it and/or configure it as the project interpreter in your IDE.

```shell
conda activate dask_introduction
```

### Dependecies installation

Finally, you must install the project dependencies in your new environment.

```shell
pip install -r requirements.txt
```

## Execution

Just run Jupyter in you environment and enjoy :)

```shell
jupyter-lab
```
