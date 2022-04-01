# MDAnalysis Tutorial

### Setup instructions : 
* This tutorial will be followed in python version 3 and greater.
* Make sure you have installed [jupyter notebook](https://jupyter.org/install)
* Make sure [anaconda](https://docs.anaconda.com/anaconda/install/linux/) is installed.
* Create environment from the `yml` file, and activate it : 
    ```
    conda env create -f MDAnalysis_Tut.yml
    conda activate MDAnalysis_Tut
    ```
* Install the environment in a kernel. This will help us use the environment in a jupyter notebook.
    ```
    python3 -m ipykernel install --user --name=Tut
    ```
* Deactivate the environment, and start jupyter notebook : 
    ```
    conda deactivate
    jupyter notebook
    ```
* Open the `Starter.ipynb` notebook
* Execute the first cell by clicking on the cell, and pressing `Shift + Enter`. Make sure all of the imports work. Any warnings are fine, but make sure there are no errors.