# terminal command for conda

## Virtual Environment
check below link for documentation
https://docs.conda.io/projects/conda/en/4.6.0/user-guide/tasks/manage-environments.html
### Create a Virtual Environment
conda create -n crypto (-n: Name of the Virtual Environment)
conda create --name pytorch

conda create -n crypto python=3.8 numpy pandas scipy (Can specify python version and install libraries together)

### Activate a Virtual Environment
activate crypto (by activating the virtual environment, the enviornment name will apear at the beginning of the command prompt in parentheses)

### exit current Virtual Environment/deactivate
conda deactivate

### Remove virtual envionment
conda env remove -n ENV_NAME

### Check environments in system
conda info --envs
conda env list


# jupyter notebook
## Install jupyter notebook
conda install -c conda-forge jupyterlab (see add channel in the following text to avoid using -c conda-forge)

## Open jupyter notebook in conda
jupyter-notebook

# install a library 
## if the library exist in conda
conda install numpy

conda install pandas matplotlib pillow seaborn

## if the library does not exist in conda
conda install pip

pip install cryptocompare

pip intsall tf-nightly

# Manage library
## Check to see if a package you have not installed named "beautifulsoup4" is available from the Anaconda repository
conda search beautifulsoup4

## Install this package into the current environment
conda install beautifulsoup4

## Check to see if the newly installed program is in this environment
conda list

# Check conda version
conda --version

# update conda
conda update conda

# Conda add a channel (conda-forge) and set priority
conda config --add channels conda-forge

conda config --set channel_priority strict

# get virtual environment info
conda info --envs

# Conda change python version
conda install python=3.8.6

# list files in current directory
$ ls

$ ls -l

# list invisible files in current directory
ls -a

# Directory
dir

# change directory to specified directory
cd directory

# go back to home directory
cd

# go to the root level of your startup disk
cd/

# go to the directory above the one you’re currently in
cd ..

# go back to the directory you were in before the last time you issued the cd command
cd -

# Make a new folder/directory
mkdir project_name

# Check python version
python --version

# Access the path (bash profile) and make a alias
nano ~/.bash_profile

under the Setting PATH for Python 3.9.x

alisa python=python3

# Check all installed packages
pip3 list

# check python version
python --version

# Check which Virtual Environment is activated
which python

# Check packages versions
pip freeze

# Save current packages versions to a requirement text file
pip freeze > requirements.txt


