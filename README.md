## PXT203 Open Data

This repo contains jupyter notebooks adapted from those written for the first GW Open Data Workshop.
The original content lives in https://github.com/gw-odw/odw-2018 and is licensed under the GPL.

### Contents

This repo consists of a short series of connected notebooks:

1. [gwosc.ipynb](./gwosc.ipynb) - how to access GW open data
1. [gwpy-timeseries.ipynb](./gwpy-timeseries.ipynb) - reading GW open data timeseries
1. [gwpy-psd.ipynb](./gwpy-psd.ipynb) - processing GW data in the frequency-domain
1. [gwpy-q.ipynb](./gwpy-q.ipynb) - visualising GW data with the Q-transform
1. [pycbc.ipynb](./pycbc.ipynb) - matched filtering GW data for signal identification

### How to run the notebookes

#### Online

The easiest thing to do is to run the notebooks from mybinder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/duncanmmacleod/pxt203-open-data/master)

#### Local

If you choose to install software locally, please note that this will not work on Windows.
I recommend using conda for this, so:

1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

1. Install the environment for the notebooks:

   ```
   $ conda env create -f environment.yml
   ```
