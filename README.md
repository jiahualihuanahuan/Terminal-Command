# terminal command


# Create a Virtual Environment
## Mac
python -m venv project_name
## Windows
python -m venv project_name\venv
## Conda Command
conda create -n venv_name python=3.7 numpy scipy keras-gpu

# Activate a Virtual Environment
## Mac
source project_name/bin/activate
## Windows
project_name\venv\Scripts\activate.bat
## Conda Command
activate venv_name

# exit current Virtual Environment/deactivate
## Mac
deactivate

## Windows
deactivate

## Conda Command
conda deactivate

## Conda add a channel (conda-forge) and set priority
conda config --add channels conda-forge
conda config --set channel_priority strict

## Conda change python version
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



# Check which Virtual Environment is activated
which python

# Check packages versions
pip freeze

# Save current packages versions to a requirement text file
pip freeze > requirements.txt

# Remove virtual envionment
## Windows
rmdir project_name /s












