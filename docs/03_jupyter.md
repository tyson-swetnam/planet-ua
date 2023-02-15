# Featured Planet Labs Notebooks

Planet supports some featured notebooks in their GitHub Organization

[https://github.com/planetlabs/notebooks](https://github.com/planetlabs/notebooks){target=_blank}

To use the notebooks in CyVerse, you can use `git` to clone the repository to your running JupyterLab

1) Open the Terminal :octicons-terminal-24: option in the Jupyter Lab Console

2) Make sure you're in the main working directory, you can use the `cd` "change directory" command to do this

3) Clone the repository to the working directory,

```
git clone --depth 1 https://github.com/planetlabs/notebooks.git
```

After a few seconds, the repository should show up as a new folder called `notebooks` in the left file browser tree. If not you can refresh :material-refresh: the file browser

4) In the `notebooks` directory, there is an `environment.yml` file that you can use `conda` or `mamba` to create a new environment for the notebooks.

We have already created an environment called `planet` for this workshop - but you can practice by creating the suggested environment.

??? Info "Creating a Python environment 

    We recommend using a package manager like `pip` or `conda` to manage your Python environments.

    Here we use `conda` with a secondary package manager called []`mamba`](https://mamba.readthedocs.io/en/latest/){target=_blank}

    Open the Terminal :octicons-terminal-24:

    In the same directory as the `environment.yml` type the following:

    ```
    mamba env create -f environment.yml
    ```

    or

    ```
    conda env create -f environment.yml
    ```

    select "Yes"

    