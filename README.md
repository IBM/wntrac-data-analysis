# WNTRAC Data Analysis
This repository contains analysis of COVID-19 Non-pharmaceutical Interventions events
data recorded in the [WNTRAC dataset](https://github.com/IBM/wntrac). Analysis has
done for a few African countries, but they can be extended to other countries as the
dataset contains worldwide events. Four notebooks are included in this repository

### WNTRAC Descriptive Statistics
The notebook `wntrac_descriptive_statistics.ipynb` includes analysis of
[WNTRAC dataset](https://github.com/IBM/wntrac/blob/master/data/README.md)
by comparing Non-pharmaceutical Interventions implemented worldwide against
those implemented by Uganda, DRC Congo, Senegal & Nigeria.
Earlier version of this analysis were presented in our
[paper](https://www.nature.com/articles/s41597-021-00878-y) in figures 6-12 generation code.

### WNTRAC Correlation Analysis
The notebook `wntrac_correlation_analysis.ipynb` includes correlation analysis of
NPIs, `beta` transmission parameter and COVID-19 cases data for 6 African countries,
including Uganda, DRC Congo, Senegal, Nigeria, Kenya & South Africa.

### WNTRAC Adherence Index
The notebook `wntrac_adherence_index.ipynb` describes and shows derivations of WNTRAC adherence index
by weighting the sum of
[Oxford Stringency Index](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker)
(SI) and Compliance Score (CS).

### Interrupted Time Series Analysis
This tutorial pertains to training and evaluating an interrupted time series model
in Python using the open-source Prophet library by Facebook Inc.
(https://facebook.github.io/prophet/)

## How to run the notebook
The notebooks are standalone and can be run independently. We recommend running them 
in the [IBM Cloud PAK for Data](https://dataplatform.cloud.ibm.com/login?context=cpdaas)
and follow the instructions there.

The notebooks can also be run locally by ensuring that a local python3
version is installed in the machine, and `pip3 install ..` all the missing libraries 
that have been imported in the notebooks.


