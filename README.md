# bravehins_classes
A repo with new bravehins dataset build based on data from Autoseg website

# Installation
To set up this project follow below steps:

0. Clone the repository.
```sh
git clone website.git
cd bravehins_classes
```
1. create the conda environment from the 'environment_h2o.yml file
```sh
conda env create -f environment_h2o.yml 
```
2. Activate the environment:
```sh
conda activate bravehins_h2o_env
```

3. Install the project in editable mode so changes in src/ are automatically picked up:
```sh
pip install -e .
```

4. Now one can import your local functions to notebooks like:
```python
from my_package.helpers import sigmoid
```

# Data
The data for this project are stored in ... 

# Purpose
