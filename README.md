# Cross-city Landuse classification of remote sensing images via deep transfer learning


# Introduction
This repository is for the codes of paper [Cross-city Landuse classification of remote sensing images via deep transfer learning](https://www.sciencedirect.com/science/article/pii/S1569843223001826)

# Environment setting
## 1. Set the env path
In file ".envPath", replace "/directory-to-current-folder" with the directory of this folder. For example, "/user/project/Cross-cityDTL"

## 2. Install conda (conda 4.10.1, where the codes are tested)
[Please refer to the anaconda documentation](https://docs.anaconda.com/anaconda/install/)

## 3. Create the conda env
```bash
conda env create -f environment.yml #Create env from yml file
conda activate LCZ_TRANSFER #activate the conda env
```
# File descriptions
## Data
The folder stores data for all experiments
## Experiments
This folder includes scripts that run the algorithms shown in the paper. To re-run our experiments, please checkout this folder.
## SRC
This folder contains python libs that support the experiments
## Prediction
This folder contains scripts that produce classification maps
## Experiments_results.xlsx
This excel shows all experiments results that we report in the paper

# Citation

@article{zhao2023cross,<br/>
title={Cross-city Landuse classification of remote sensing images via deep transfer learning},<br/>
author={Zhao, Xiangyu and Hu, Jingliang and Mou, Lichao and Xiong, Zhitong and Zhu, Xiao Xiang},<br/>
journal={International Journal of Applied Earth Observation and Geoinformation},<br/>
volume={122},<br/>
pages={103358},<br/>
year={2023},<br/>
publisher={Elsevier}<br/>
}



