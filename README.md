# ohbm-handson-test
## Test repository for the Handson session for Reproducibility 

## Context
Tesyt repo for reproducibility

## How to get this content

## Data description
Data

## How to install 

First create and activate a virtual environment:

```
conda create -n handson-test python=3.6
conda activate handson-test 
```

First install the packages with pip after navigating to the repo root folder:

```
pip install -r requirements.txt
```

Then install the BrainStat package:

```
git clone https://github.com/MICA-MNI/BrainStat.git
cd BrainStat
python3 setup.py build
python3 setup.py install
```

## How to run the analysis

Navigate to the code folder, then run the script:

```
python3 analysis_01.py
```

How to

## Binder access
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AgustinSolano/ohbm-handson-test.git/HEAD)

```
```
