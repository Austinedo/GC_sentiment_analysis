# GC_sentiment_analysis_project

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

A Sentiment Analysis for Great Clips Reviews Online

## Project Organization

```
│
├── README.md          <- The top-level README for those viewing this project.
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         gcsa and configuration for tools like black
├── data (not included in public repository)
│   ├── raw/external   <- Data from third party sources/Original immutable data (.csv | .json | XML | etc.)
│   ├── interim        <- Intermediate data that has been transformed.
│   └── processed      <- The final, canonical data sets for modeling.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Working Jupyter notebooks (rough and polished notebooks)
│
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── gcsa   <- Source code for use in this project. (will RENAME to 'src')
    │
    ├── __init__.py             <- Makes gcsa a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

