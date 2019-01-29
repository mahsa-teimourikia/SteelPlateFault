# Steel Plate Fault Analysis

The goal of this document is to describe the approach used to analyse the dataset related to the Steel Plates Faults at the following link:
http://archive.ics.uci.edu/ml/datasets/steel+plates+faults

The dataset includes 1941 observations, and 27 features. The data is already labeled, and there are 7 types of steel plate faults that are added to the dataset as 7 fields representing the one-hot-encoding of the label.

## Installations and Usage Giudelines
For this project I have been using the Anaconda distribution version 1.8.7 with python version 3.6.5. However, the normal installation of python should also work.

Here you may find the required modules that have been used in this project. The codes are written in Python 3.

* seaborn 0.9.0
* pandas 0.23.4
* numpy 1.15.1
* matplotlib 2.2.3
* sklearn 0.19.2
* scipy 1.1.0

For the complete list of requirements and their dependencies please take a look at the requirements.txt file provided. To replicate my exact environment in anaconda distribution you may use the following command using the machine-learning.yml file provided:
```
conda env create -f machine-learnin.yml
```
