# Modeling corona virus spread in Germany

No guarantees that any of this is correct or that any of the
predictions will come true.

## Looking

Just look at the outputs by opening the notebooks:

* without mortality: [github](https://github.com/BenjaminBossan/corona/blob/master/model_corona_virus.ipynb) [nbviewer](https://nbviewer.jupyter.org/github/BenjaminBossan/corona/blob/master/model_corona_virus.ipynb)
* with mortality [github](https://github.com/BenjaminBossan/corona/blob/master/model_corona_virus_with_mortality.ipynb) [nbviewer](https://nbviewer.jupyter.org/github/BenjaminBossan/corona/blob/master/model_corona_virus_with_mortality.ipynb)

## Running

First you need to clone this repo and the repo containing the data:

```bash
git clone https://github.com/CSSEGISandData/COVID-19.git
git clone https://github.com/BenjaminBossan/corona.git
```

Inside `corona/`, create a Python3 virtual enviroment with your favorite tool and
install the requirements from `requirements.txt`, e.g. using pip, and
start a notebook server:

```bash
# create virtual environment
pip install -r requirements.txt
jupyter notebook
```

Navigate to the notebook server (e.g. `localhost:8888`) and open the
notebook you want to edit.
