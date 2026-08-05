# Requirements

In order to run these components you need to have conda (Miniconda or Anaconda), MLflow, and W&B installed.
From the repository root, install the local component package and its compatible dependencies with::

    > python -m pip install -e ./components

Each component directory is a separate MLflow Project. For example, inspect the download component with::

    > python components/get_data/run.py --help

Use ``mlflow run components/get_data ...`` to execute it with the environment declared in its own
``conda.yml``.
