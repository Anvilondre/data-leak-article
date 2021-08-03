# Leaky tabular data
## Description
This is a repo with code used for my article on TypeChi  
Data comes from [Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales/) Kaggle competition

## Setup
To install needed packages in the base environment you can use  
```
pip install -r requirements.txt
```
However, it's advisable to use a dedicated environment. 
Here's a list of commands you may use to set up a conda environment:
```
conda create --prefix ./venv python=3.9
conda activate ./venv
pip install -r requirements.txt
```
To launch Jupyter simply use
```
jupyter notebook
```