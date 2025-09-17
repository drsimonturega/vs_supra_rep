# vs_supra_rep
## Contents

* Introduction
* Code development
* Installation instructions
* Usage instructions
* File structure of the project
* License information

## Introduction

This is a reanalysis of the predictive model from the "Virtual screening for high affinity guests for synthetic supramolecular receptors", https://doi.org/10.1039/C5SC00534E. The original model was a multivariate linear regression run in microsoft excel. I am going to move this to python for use in teaching. Initialy I will keep the experiemnt as close to the original literature as possible for use in my teaching on a university teaching module "Introduction to data science" at Hallam university.
## Code development



## Usage instructions

Currently we make a local lib folder ```mkdir lib``` in our home folder change to that folder.

## File structure of the project

Initaly there are five python files, *dat_tran.py*, *datframe_inf.py*, *datframe_tran.py*, *plotter.py* and *db_utils.py* that contains the classes and methods used in this project. The each file contains a class of related methods for a specific part of the analysis the methods are run in a juypter note book *EDA.iypnb*.

The *db_utils.py* contains a class ```RDSDatabaseConnector()``` that has a methods for extracting data from local or remote databases. The *dat_tran.py* file contains the class ```DataTransform()``` with methods for converting the types of columns and removing unwanted characters. A third python file *datframe_inf_.py* houses the class ```DataFrameInfo()```, this class contains methods for running some statistical analysis for example saving the numerical out put as a **.csv* files when desired.  The python file *datframe_tran.py* contains the class ```DataFrameTransform()``` with methods for cleaning data, imputing missing data, correcting skewed data and removing highly correlated columns from the data. The fith file ```plotter.py``` contains the ```Plotter()``` class that has methods for plotting the data we explore in data science projects project.



## License information

