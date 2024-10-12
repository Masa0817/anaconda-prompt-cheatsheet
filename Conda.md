# Anaconda Prompt Cheatsheet

This file contains a collection of essential Anaconda Prompt commands for managing Python environments, installing packages, and working with Anaconda efficiently.

## Environment Management

### Create a New Environment
```bash
conda create -n myenv python=3.10
```

### Create a New Environment
```bash
conda activate myenv
```

### Deactivate an Environment
```bash
conda deactivate
```
Deactivates the currently active environment.

### List All Environments
```bash
conda env list
```

### Remove an Environment
```bash
conda remove -n myenv --all
```


## Package Management

### Install a Package
```bash
conda install package_name
```

### Install Multiple Packages
```bash
conda install numpy pandas matplotlib seaborn scikit-learn scipy statsmodels jupyter notebook ipython sympy xlrd openpyxl xlsxwriter requests beautifulsoup4 lxml sqlalchemy
```
### List Installed Packages
```bash
conda list
```
### Update a Package
```bash
conda update package_name
```

### Remove a Package
```bash
conda remove package_name
```


## Anaconda Management

### Update Conda
```bash
conda update conda
```

### Update All Packages in the Environment
```bash
conda update --all
```

### Check Conda Info
```bash
conda info
```

### Search for a Package
```bash
conda search package_name
```


## Jupyter Notebook Management
### Install Jupyter Notebook
```bash
conda install jupyter
```

### Launch Jupyter Notebook
```bash
jupyter notebook
```

## Miscellaneous

### List Available Python Versions
```bash
conda search python
```

### Create Environment with a Specific Package
```bash
conda create -n myenv python=3.9 numpy pandas
```

### Clone an Existing Environment
```bash
conda create --name newenv --clone oldenv
```