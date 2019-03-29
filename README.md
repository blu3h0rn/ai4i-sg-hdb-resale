![AI4I Banner](https://gallery.mailchimp.com/f98d5ac0a3fbbdcdda35136ab/images/2002af76-5fd4-4185-9d49-28558b6b8772.png)
# Hands-on Machine Learning Workshop (SG HDB Resale)
This repository contains resources for AI for Industry's Hands-on Machine Learning Workshop (SG HDB Resale)

# Instructions/Guide

## Ways to get these resources on your own local machine

1. Simply click on the `Clone or download` button and `Download ZIP`
    + After downloading, simply extract contents to desired directory, possibly your desktop

2. Through `git`
```
cd 'path/to/desired/directory'
git clone https://github.com/ryzalk/ai4i-sg-hdb-resale.git
```

## Setting up virtual/conda environment
To set up an environment where the relevant packages can be installed so that you can employ whatever we will be used for today's workshop:

+ For conda (recommended for you to install Anaconda as this method is easier)
```bash
cd 'path/to/ai4i-sg-hdb-resale'
conda env create -f hdbresale19v2.yml
# Now to activate environment
conda activate hdbresale
# After acvtivating environment, open up Jupyter Notebook
jupyter notebook
```

+ For virtualenv
```bash
cd 'path/to/ai4i-sg-hdb-resale'
virtualenv hdbresale

# Now to activate environment
# For Windows
hdbresale\Scripts\activate
# For Mac OS/Linux
source hdbresale/bin/activate

pip install pandas numpy
pip install sqlalchemy
pip install matplotlib
pip install scikit-learn
pip install flask
pip install flasK_restful
python3 -m pip install jupyter

# After acvtivating environment, open up Jupyter Notebook
jupyter notebook
```