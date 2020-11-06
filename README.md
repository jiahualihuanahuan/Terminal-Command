# terminal command

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

# Create a Virtual Environment
## Mac
python -m venv project_name
##
python -m venv project_name\venv

# Activate a Virtual Environment
## Mac
source project_name/bin/activate
## Windows
project_name\Scripts\activate.bat

# exit current Virtual Environment
deactivate

# Check which Virtual Environment is activated
which python

# Check packages versions
pip freeze

# Save current packages versions to a requirement text file
pip freeze > requirements.txt

# Remove virtual envionment
## Windows
rmdir project_name /s












