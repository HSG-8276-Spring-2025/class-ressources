---
id: anaconda
title: Anaconda and conda
previous_page: 
next_page: conda-env
---

## Anaconda Distribution

Anaconda Distribution is a Python/R data science distribution that contains:
- **Anaconda Navigator**: a desktop application built on conda, with options to launch other development applications from your managed environments
- **conda**: a package and environment manager for your command line interface
- Over 300 automatically-installed packages that work well together out of the box

## Installing Anaconda
Install Anaconda from the [download page](https://www.anaconda.com/download/success)


## Anaconda navigator
Cf. Overview [page](https://docs.anaconda.com/navigator/overview/)
![](https://docs.anaconda.com/_images/nav-learn1.png)

- **Home page**: Install or launch popular graphical Python applications that work well with Navigator. We will mainly uses:
  - [Jupyter Notebook](https://docs.jupyter.org/en/latest/)
  - [VS Code](https://code.visualstudio.com/docs)
    - Most useful VS code extensions 
- **Environments page**: allows you to manage installed environments, packages, and channels.

## Conda: Working with the environements

Conda is an open source package management and environment management tool for Python and other languages. Whenever you use Python, you will be working in a Python environment, which contains the specific Python version you are running on and various Python packages with specific package versions and specifications.

Cf. this [starting guide](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html) from conda. 

The environement used in the class can be found [here](https://raw.githubusercontent.com/HSG-8276-Spring-2025/class-ressources/refs/heads/main/hsg-spring2025.yaml). You should be able to import the environment using the following command:
```bash
conda env create -f https://raw.githubusercontent.com/HSG-8276-Spring-2025/class-ressources/refs/heads/main/hsg-spring2025.yaml
```

Alternativelly, you can import this environment in the Anaconda Navigator (see Environment page).

In VSCode, you can access the conda environment by looking for your environement in the "Python: Select Interpreter" option in the command palette (Ctrl+Shift+P). 

You can also create a new environment from the command palette by typing "Python: Create Environment" and following the prompts.

![VSCode conda env](img/vscode-python%20environment.png)


### References: 

https://conda.io/en/latest/

