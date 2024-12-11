# Training ML Models to Classify text messages as SPAM or HAM
Group Ham: Alikhan Manat, Aleksandar Miloradovic & Jakob Huber

In this Project we set out to train different ML Models to classify Text from the SMS Spam Dataset. We trained 3 different Models trying to get an accuracy as good as possible and also including some Tools to Explain the Models. 

To Run this Notebook with the provided Environment

- You need to have Anaconda or Miniconda installed
- Use Anaconda Prompt to execute the following commands
- create the Environment conda ```env create -f environment.yml```
- Activate the Environment: ```conda activate hamEnv```
- start your Jupiter Notebook: ```jupyter lab```

If you want the kernel to show up in your Jupiter Interface you might need to additionally run:
    ```python -m ipykernel install --user --name=hamEnv --display-name "Python (hamEnv)"```

If ipykernel is not installed additionally run
    ```pip install ipykernel```

With this setup if you open your jupiter notebok you can simply select the hamEnv as your kernel. This gives you a fixed and working environment including all necessary dependencies without any additional installs!