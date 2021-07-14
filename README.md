# Climate-Friendly Food Systems (CFFS) Labelling Project

UBC Institute for Resources, Environment and Sustainability (IRES)

Created by Silvia Huang


Description
------------
A reproducible framework for analyzing the climate intensity of menu items at the UBC campus by producing the weighted
metric that informs the choice of icon for each menu item.


Prerequisites
------------
Python 3


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── raw            <- Raw recipes data from Optimal Control
    │   ├── final          <- Final calculation results
    │   ├── preprocessed   <- Preprocessed datasets
    │   ├── cleaning       <- Cleaned datasets
    │   ├── mapping        <- Mapped items to emission factors
    │   └── external       <- External dataset for support
    │
    ├── notebooks
    │   └──0_methodology and data source.ipynb
    │   └──1_data preprocessing.ipynb
    │   └──2_data cleaning and mapping.ipynb
    │   └──3_exploratory data analysis.ipynb
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
