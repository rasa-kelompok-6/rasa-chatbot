# rasa-chatbot

Rasa chatbot

# Steps before usage

## Install anaconda

[Windows](https://www.anaconda.com/products/individual#windows)

[Any other OS](https://docs.anaconda.com/anaconda/install/)

# Run
Open anaconda prompt

Go to target directory with anaconda prompt

Check available environments with `conda info --envs`, or create one with `conda create --name 'env-name' python=='version'`. Example `conda create --name RasaInstall python==3.8`

Activate with `conda activate 'env-name'`, example `conda activate RasaInstall`

If you create a new environment, run `conda install json`, `conda install tensorflow`, and `pip install rasa`. And then initialize with `rasa init`

Otherwise, just run `rasa run`

# Dependencies

* Tensorflow
