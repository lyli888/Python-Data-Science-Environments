# Environment Setup: PythonData & PythonAdv

### PythonData Installation Via GitBash
conda --version [confirm Anaconda installation]
pwd [ensure environment file is in current directory] ls [lists everything in current directory] cd [change directory] cd .. [navigate to top menu]
conda create -n PythonData --file requirement.txt python=3.6 [create environment, answer y when asked]
conda env list [lists environments with * next to active one]
conda activate PythonData [OR] source activate PythonData [if you anaconda installed for all users]

### PythonAdv (Machine/Deep Learning, Neural Networks)
conda create -n PythonAdv python=3.6
conda activate PythonAdv or source activate PythonAdv
conda install numpy pandas requests scipy scikit-learn matplotlib
conda install tensorflow py4j pyspark jupyter_client nb_conda_kernels keras ipykernel
