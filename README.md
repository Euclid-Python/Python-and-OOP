<a href="http://www.cosmostat.org/" target_="blank"><img src="http://www.cosmostat.org/wp-content/uploads/2017/07/CosmoStat-Logo_WhiteBK.jpg" width="400"></a>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Euclid-Python/Python-and-OOP/master)

# Pythonic and Object-Oriented Programming
---

> Author: <a href="http://www.cosmostat.org/people/sfarrens" target="_blank" style="text-decoration:none; color: #F08080">Samuel Farrens</a>  
> Email: <a href="mailto:samuel.farrens@cea.fr" style="text-decoration:none; color: #F08080">samuel.farrens@cea.fr</a>  
> Year: 2019  
> Version: 1.0

---
<br>

## Contents
---

1. [Set Up](#Set-Up)
   * [Requirements](#Requirements)
   * [Running Remotely](#Running-Remotely)
   * [Running Locally](#Running-Locally)
1. [Notebooks](#Notebooks)
   * [Pythonic Programming](#Pythonic-Programming)
   * [Object-Oriented Programming](#Object-Oriented-Programming)

## Set Up
---

### Requirements

In order to run the tutorial notebooks tutees will need to have the following installed:

* <a href="https://www.python.org/" target_="blank">Python</a> (require >=3.5)
* <a href="http://jupyter.org/" target_="blank">Jupyter</a> (recommend >=1.0.0)
* <a href="http://www.numpy.org/" target_="blank">NumPy</a> (recommend >=1.16)

### Running Remotely

ll of the tutorials can be run remotely by launching the repository
[Binder](https://mybinder.org/v2/gh/Euclid-Python/Python-and-OOP/master). No further set up is required.

### Running Locally

In order to run the tutorials offline, please follow these steps:

1. Download or clone the GitHub repository.

    <img src="http://www.cs.williams.edu/~dbarowy/cs334s18/assets/tutorials/github/github-clone-button.png" width="300">

    *e.g.*

    ```bash
    git clone https://github.com/Euclid-Python/Python-and-OOP.git
    ```

2. Install the tutorial dependencies.

    This can be done using `pip` as follows:

    ```bash
    pip install -r requirements.txt
    ```

      or using `conda` as follows:

    ```bash
    conda env create -f environment.yml
    conda activate pyoop
    ```

3. Finally, the notebooks can be launched by running:

    ```bash
    jupyter notebook
    ```

## Notebooks
---

### Pythonic Programming

1. [Pythonic Thinking](./Pythonic.ipynb)

### Object-Oriented Programming

1. [The Anatomy of a Python Class: Part I](./Classes_I.ipynb)
1. [The Anatomy of a Python Class: Part II](./Classes_II.ipynb)
