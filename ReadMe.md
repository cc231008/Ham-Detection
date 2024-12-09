To Run this Notebook with the provided Environment

- You need to have installed Anaconda or Miniconda
- create the Environment in your command line: conda env create -f environment.yml
- Activate the Environment: conda activate hamEnv
- start your Jupiter Notebook: jupyter notebook

If you want the kernel to show up in your Jupiter Interface you need to additionally run:
    python -m ipykernel install --user --name=hamEnv --display-name "Python (hamEnv)"

If ipykernel is not installed additionally run
    pip install ipykernel

With this setup if you open your jupiter notebok you can simply select the hamEnv as your kernel and have a fixed and working environment without any additional installs!
