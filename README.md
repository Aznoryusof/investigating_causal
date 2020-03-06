# Investigating Causal Relationships
This repository investigates the different modern approaches available to uncover causal factors behind employees' staying intentions within an organisation, provided as Jupyter Notebooks.

#### -- Project Status: [Active]

## Project Intro/Objective
The purpose of this project is to study in detail the various statistical methods and APIs available on identifying causal relationships, and serves as a quickstart guide to anyone trying to better understand how to apply these methods on their dataset.

### Methods Used
|Method     |  Path to Jupyter Notebook   | 
|----------------|-----------------------------|
|1. Structural Equation Modelling| notebooks/Analysis with Structural Equation Modelling.ipynb|
|2. Bayesian Networks| notebooks/Analysis with Bayesian Networks.ipynb  |


### Technologies
* Python
* R
* Pandas, Jupyter
* Levaan, semPlot
* CausalNex

## Project Description
The data that would be used for this task is based on a survey of employees’ attitudes and perception towards their workplace. The questionnaire items included questions which attempts to represent the following latent constructs: 
1) Organisational Commitment
2) Attitudes Towards Co-Workers
3) Environmental Perceptions
4) Job Satisfaction
5) Staying Intentions

The main objective is to build a suitable model to predict the influences of the different factors on employees’ staying intentions.

## Installation
Firstly, clone the repository to a folder of your choice. 

Next install the necessary libraries

1. Create an environment with a specific version of Python
	```
   conda create -n causal python=3.6
   activate causal
   ```

2. Install libraries from requirements.txt using conda. For windows, run the following in the terminal:
	```
   for /f %i in (requirements.txt) do conda install --yes %i
   ```

Next download the necessary datasets that have been pre-processed by running the following script in the terminal
in the project's main directory.

```
python src\make_dataset.py
```

# References:
1) Structural Equation Modelling
https://www.kdnuggets.com/2017/03/structural-equation-modeling.html

2) CausalNex API 
https://causalnex.readthedocs.io/en/latest/
