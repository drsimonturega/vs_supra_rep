# vs_supra_rep
## Contents

* Introduction
* Code development
* Installation instructions
* Usage instructions
* File structure of the project
* License information

## Introduction

This is a reanalysis of the predictive model from the "Virtual screening for high affinity guests for synthetic supramolecular receptors", https://doi.org/10.1039/C5SC00534E. The original model was a multivariate linear regression run in microsoft excel. I am going to move this to python for use in teaching. Initialy I will keep the experiemnt as close to the original literature as possible, then repeat it with a current data science approach including some EDA and using sklearn to split the data in to training and test sets. This is for use in my teaching on a university teaching module "applications of data science" at Hallam university, the session is run over a 1 hr online session with an introduction to the literature, like we are still stuck in the pandemic but colab is great for this.

## Code development
This repoduces the analysis in the manuscript and then reanalysis the data using a current data science approach. The code is writen in python and run in a google colab notebook. It uses my data science library [simons_data_science_library](https://github.com/drsimonturega/simons_data_science_library) to facilitate the complettion of the task in a one hour session.
I will be include a new Python method that removes folders provided by a list. This is for incorporation into my data science library once I'm happy with the method.

## Usage instructions
Currently we run our analysis in the notebook [vs_supra_rep_002.ipynb](https://github.com/drsimonturega/vs_supra_rep/blob/main/vs_supra_rep_002.ipynb)

## File structure of the project
There are **.txt* files copied from the suplimentory information in the manscript. There are also two **.ipynb* one of which we will run in google colab in our session.



## License information

GNU General Public License v3.0

