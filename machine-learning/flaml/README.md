# FLAML

Author: Dr. Zhonghua Zheng ([zhonghua.zheng@outlook.com](mailto:zhonghua.zheng@outlook.com))

Last Updated July 21, 2021

## Introduction

This repo contains the files for conda environments. The basic conda environment is `environment.yml`. It consists of:

- Python=3.8.0
- Jupyter
- data processing
  - numpy 
  - pandas
  - xarray (with netCDF support)
  - scipy
- machine learning
  - [FLAML](https://github.com/microsoft/FLAML)
  - scikit-learn
- mapping & plotting
  - matplotlib

## Usage

**Step 0: Install [Anaconda](https://docs.anaconda.com/anaconda/install/index.html) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)**

**Step 1: Create the environment the running the code below**

```bash
$ conda env create -f environment.yml
```



