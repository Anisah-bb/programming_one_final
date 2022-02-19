# The five mosquiteers
* * *
A case study about the attractiveness of humans to mosquitoes. 


## Description
* * *
This repository contains the code to run a dashboard, which shows an infographic of a study about the association between admission type and readmission rates in patients with diabetes. 

### Data
The process datasets can be found at https://data.world/uci/diabetes-130-us-hospitals-for-years-1999-2008/workspace/file?filename=dataset_diabetes%2Fdiabetic_data.csv and https://data.world/uci/diabetes-130-us-hospitals-for-years-1999-2008/workspace/file?filename=dataset_diabetes%2FIDs_mapping.csv

### Data description

The different columns of the table are described in the documentation directory [here](https://www.hindawi.com/journals/bmri/2014/781670/tab1/)

## Installation
* * *

### Single install
The easiest way to install all the required packages is via conda. How to install conda on your system can be found [here](https://docs.anaconda.com/anaconda/install/index.html).


### Multiple installs
An other option is to install each package seperately, either with conda or pip.

conda:
```bash
  conda install <PACKAGE>=<VERSION>
```

pip
```bash
  pip install <PACKAGE>==<VERSION>
```

> NOTE: make sure to use the correct versions, which are listed [here](#packages).

## Getting started
* * *
To open the dashboard run the [dashboard_mosquitoes.ipynb](Dashboard/dashboard_mosquitoes.ipynb) notebook from top to bottom.


## Requirements
* * *
| Software                          | Version  |
| --------------------------------- | :------: |
| [Python](https://www.python.org/) | `3.9.7`  |    


## Packages
* * *
| Package                                              | Version  |
| ---------------------------------------------------- | :------: |
| [numpy](https://numpy.org/)                          | `1.21.2` |
| [pandas](https://pandas.pydata.org/)                 | `1.3.3`  |
| [bokeh](https://bokeh.org/)                          | `2.3.3`  |
| [panel](https://panel.holoviz.org/)                  | `0.12.1` |
| [holoviews](https://holoviews.org/)                  | `1.14.6` |
| [hvplot](https://hvplot.holoviz.org/)                | `0.7.3`  |
| [scipy](https://scipy.org/)                          | `1.7.1`  |
| [jupyter](https://jupyter.org/)                      | `1.0.0`  |
| [statsmodel](https://www.statsmodels.org/)           | `0.12.2` |
| [pathlib](https://pathlib.readthedocs.io/en/pep428/) | `1.0.1`  |




## License
* * * 
This project contains a MIT.



## Legal
* * * 

This study is based on a preexisting HIPAA compliant dataset that contains no personally identifiable information. Due to the deidentified nature of the datasets obtained; this study was not considered human subjects research nor required consent per the Helsinki Declaration and was therefore exempt from VCU Institutional Review Board review.