# Modeling corona virus spread in Germany

No guarantees that any of this is correct or that any of the
predictions will come true.

## Looking

Just look at the outputs by opening the notebooks:

* without mortality: [github](https://github.com/BenjaminBossan/corona/blob/master/model_corona_virus.ipynb) [nbviewer](https://nbviewer.jupyter.org/github/BenjaminBossan/corona/blob/master/model_corona_virus.ipynb)
* with mortality [github](https://github.com/BenjaminBossan/corona/blob/master/model_corona_virus_with_mortality.ipynb) [nbviewer](https://nbviewer.jupyter.org/github/BenjaminBossan/corona/blob/master/model_corona_virus_with_mortality.ipynb)

## Running

First you need to clone this repo and the repo containing the data,
then copy the notebooks to the repo containing the data (you can skip
the last step but then need to adjust the notebook paths):

```bash
git clone https://github.com/CSSEGISandData/COVID-19.git
git clone https://github.com/BenjaminBossan/corona.git
cp corona/*.ipynb COVID-19/
cd COVID-19/
```

Create a Python3 virtual enviroment with your favorite tool and then
install the requirements from `requirements.txt`, e.g. using pip, and
start a notebook server:

```bash
# create virtual environment
pip install -r requirements.txt
jupter notebook
```

Navigate to the notebook server (e.g. `localhost:8888`) and open the
notebook you want to edit.
