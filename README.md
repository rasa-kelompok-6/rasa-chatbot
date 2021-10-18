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

## If you create a new environment
run `conda install ujson`, `conda install tensorflow`, and `pip install rasa`. If you want a new project, then initialize with `rasa init`

## If you dont
`rasa shell` to run on shell

`rasa train` if you want to train model with new data

`rasa run -m models --enable-api --cors "*"` if you want to run on website. Then open index.html on browser

# Dependencies

* Tensorflow

# TODO

* Add test stories, entitas, slot, custom actions, basis data, dan lainnya untuk menaikan nilai
