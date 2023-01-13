# Predict Bike Sharing Demand with AutoGluon

## Overview

In this project, AutoGluon library is used to train several models for the Bike Sharing Demand competition in Kaggle.

Tabular Predictions are used to fit data from CSV files provided by the competition.

Bike-sharing demand is highly relevant to related problems companies encounter, such as Uber, Lyft, and DoorDash. 
Predicting demand not only helps businesses prepare for spikes in their services but also improves customer experience by limiting delays.

In the end, we submitted several entries to the competition and achieved a rank within Kaggle.
A report of findings is also created to share publicly on Kaggle to showcase work.

### Dependencies

```
Python 3.7
MXNet 1.8
Pandas >= 1.2.4
AutoGluon 0.2.0 
```

### Installation
For this project, it is highly recommended to use Sagemaker Studio from the course provided AWS workspace. This will simplify much of the installation needed to get started.

For local development, you will need to setup a jupyter lab instance.
* Follow the [jupyter install](https://jupyter.org/install.html) link for best practices to install and start a jupyter lab instance.
* If you have a python virtual environment already installed you can just `pip` install it.
```
pip install jupyterlab
```
* There are also docker containers containing jupyter lab from [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html).
