# Python for AI

- conda --version

# Create a Environment

- conda create -p venv python=3.12
- "-p" in the current directory
- "venv" is the name of the environment
- "python=3.12" is the version of python
- conda activate venv

- conda create -n myenv python=3.12
- "-n" installed in anaconda directory where ever it is installed

- conda activate /home/pradeep/workstation/AI/python-for-ai/venv
- conda deactivate

# Install a package

- pip install ipkernel (its required to run jupyter notebook)

# create packages

- pip install -r requirements.txt
- "-e ." export to the current directory as a package (requirements.txt)
