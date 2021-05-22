# Environment Setup: PythonData & PythonAdv

## PythonData Installation Via GitBash
### conda --version [confirm Anaconda installation]
### pwd [ensure environment file is in working directory] ls [lists files] cd [change directory] cd .. [navigate to top menu]
### conda create -n PythonData --file requirement.txt python=3.6 [create environment, answer y when asked]
### conda env list [lists environments with * next to active one]
### conda activate PythonData [OR] source activate PythonData [if you anaconda installed for all users]

## PythonAdv (Machine/Deep Learning, Neural Networks)
## conda create -n PythonAdv python=3.6
## conda activate PythonAdv or source activate PythonAdv
## conda install numpy pandas requests scipy scikit-learn matplotlib
## conda install tensorflow py4j pyspark jupyter_client nb_conda_kernels keras ipykernel


## Scikit-Learn & Tensorflow Compatibility with SciPi, Numpy Very Specific

https://www.tensorflow.org/install
https://sklearn.org/install.html
https://scikit-learn.org/stable/install.html

## pip install -U scikit-learn
## conda install scikit-learn
## conda update scikit-learn
## conda remove scikit-learn

Upgrading with pip install -U scikit-learn or uninstalling pip uninstall scikit-learn is likely fail to properly remove files installed by the conda command.
pip upgrade and uninstall operations only work on packages installed via pip install.

In order to check your installation you can use

python -m pip show scikit-learn  # to see which version and where scikit-learn is installed
python -m pip freeze  # to see all packages installed in the active virtualenv
python -c "import sklearn; sklearn.show_versions()"

## Requires the latest pip
pip install --upgrade pip

## Current stable release for CPU and GPU
pip install tensorflow

# Or try the preview build (unstable)
pip install tf-nightly

## Tensorflow Neural Network Playground - [https://www.playground.tensorflow.org]
