# Readme for cantera project.

This repo contains python files using the package cantera to solve problems related to the course
KE2060 Computational Project in Chemical Engineering

# Installing the cantera environment

After downloading the requirements.txt file you can install the needed packages with PIP or Conda.

### For installation with PIP:
You can install the environment used in this project with PIP using
the following command in the terminal (After activating your environment)

    pip install -r requirements.txt

For further information on how to handle virtual environments and packages with pip see the following: 

https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/

### For installation with Conda:

You can install the environment used in this project with Conda using
the following command in the terminal (creates new environment with packages)

    conda create --name "myenv" --file requirements.txt

or install into existing environment

    conda install --file requirements.txt

For further information on how to handle environments and packages with conda see the following: 

https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html


### The requirements.txt file

This file contains the information to install cantera but will also insatll numpy, matplotlib and scipy into your environment. 