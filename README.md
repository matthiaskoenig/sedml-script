# SED-ML script

Python based implementation of the SED-ML script examples.

For the reference SED-ML script and antimony code see: 
https://docs.google.com/document/d/1HzX0GcwoG_dcA_Zwuud0r7ICyH9WfSuJX_4lXxdJImc/edit?ts=5d37846b#

## Installation
All examples can be run with a minimal virtual environment.
Requirements are listed in 
```
# create virtualenv
mkvirtualenv sedml-script --python=python3.6
(sedml-script) pip install -r requirements.txt
(sedml-script) pip install jupyterlab

# run jupyter lab with kernel
(sedml-script) ipython kernel install --user --name=sedml-script
(sedml-script) jupyter lab
```

## Notebook examples
The notebook with outputs is [here](sedml-script.ipynb).


## TODO
- read data and plot
- read data and parameterize
- parameter scan and plot areas
- initial condition scan