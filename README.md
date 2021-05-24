# Environment Setup: PythonData & PythonAdv

## PythonData Installation Via GitBash
The specifics of altering your Python environments in Terminal/Gitbash will depend on the directory/location/specs of your initial Anaconda installation and the directory/level on which you Gitbash.
If your Windows username has spaces, some libraries will not work. As a rule, make names all lowercase no spaces
### conda --version [confirm Anaconda installation]
### pwd [ensure environment file is in working directory] ls [lists files] cd [change directory] cd .. [navigate to top menu]
### conda create -n PythonData --file requirement.txt python=3.6 [create environment from txt, answer y when asked]
### conda env list [lists environments with * next to active one]
### conda activate PythonData [OR] source activate PythonData [if anaconda installed for all users]

## PythonAdv (Machine/Deep Learning, Neural Networks)
## conda create -n PythonAdv python=3.6
## conda activate PythonAdv [OR] source activate PythonAdv
## conda install numpy pandas requests scipy scikit-learn matplotlib
## conda install tensorflow py4j pyspark jupyter_client nb_conda_kernels keras ipykernel


## Scikit-Learn & Tensorflow Version Compatibility with SciPi, Numpy Versions Very Specific

https://www.tensorflow.org/install
https://sklearn.org/install.html
https://scikit-learn.org/stable/install.html
https://sklearn.org/developers/advanced_installation.html#advanced-installation

## pip install/uninstall/update -U scikit-learn
## conda install/remove/update 

pip installer has always worked better for me than conda. Pip upgrade and uninstall operations only work on packages installed via pip install, conda update/remove works on conda install. Sometimes a library will work in Python but not in Jupyter Notebook-"pip3 install" was helpful for Python3 files in PythonData.

## For Machine Learning/Neural Network/Deep Learning, activate PythonAdv environment (conda/source activate PythonAdv) and make sure PythonAdv kernel is active in Jupyter Notebook.

In order to check your Scikit Learn installation you can use

python -m pip show scikit-learn  # to see which version and where scikit-learn is installed
python -m pip freeze  # to see all packages installed in the active virtualenv
python -c "import sklearn; sklearn.show_versions()"

## Requires the latest pip
pip install --upgrade pip

## Tensorflow
pip install tensorflow

## Tensorflow Neural Network Playground - [https://www.playground.tensorflow.org]
