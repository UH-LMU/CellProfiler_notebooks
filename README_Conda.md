# Setting up a Conda environment
These instructions should work on centrally administered workstations at the University of Helsinki.

## Install Anaconda
Find Anaconda in Software Center, install latest version.

## Download environment file and notebook(s)
The environment file is like a recipe to build a Python environment with all the necessary packages for a particular application. This repository has the following environment files:
- env\_napari.yml (installs Napari, works for moldev\_composite.ipynb)

It's best to download both the .env and the .ipynb files on C: drive, e.g. in C:\Users\username\Documents.

## Build the environment
You need to do this only once. The environment is stored on the computer.
- Open Start Menu / Anaconda / Anaconda prompt
- Run the following commands:
    - conda env create -f C:\Users\username\Documents\env_napari.yml
	
If you get a security prompt about "making changes on this computer" and asking for administrator details, answer no. The installation probably worked in any case.

## Activate environment and start Jupyter Notebook
- Open Start Menu / Anaconda / Anaconda prompt
- Run the following commands:
    - conda activate napari
	- jupyter notebook
	
This should open a browser window with Jupyter Notebook page.

## Find your notebook and run it
- Browse to the folder where you saved the .ipynb file.
- Click on the link (e.g. moldev_composite.ipynb) to start the notebook.
- Follow instructions in the notebook.

