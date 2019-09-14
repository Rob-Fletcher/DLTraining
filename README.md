# DLTraining


## Installation Instructions

Setup the Conda environment

"""bash
# Create a new environment
conda create -n dltraining python=3.7
"""

"""bash
# Install Pytorch and Jupyterlab
conda install pytorch torchvision -c pytorch
conda install -c conda-forge jupyterlab

# We will also need matplotlib
python -m pip install -U pip
python -m pip install -U matplotlib
"""

To be able to display live metrics we will use tensorboard. This requires
installing tensorflow and tensorboard to get the full functionality.

"""bash
conda install tensorflow

# Tensorboard needs a module called past so we should install future (i know...)
pip install future

pip install tqdm
"""
