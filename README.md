# Generative Models For Cryptographic Key Generation

A research-oriented project exploring the use of generative machine learning models to create strong, unpredictable cryptographic keys. Focuses on enhancing key randomness and entropy while maintaining compliance with modern security standards and cryptographic best practices.

## Project Organization

```
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── deployment         <- Serving, Docker, API, CI/CD, etc.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         generative_models_for_cryptographic_key_generation and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── generative_models_for_cryptographic_key_generation   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes generative_models_for_cryptographic_key_generation a Python module
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
    ├── pipelines               <- End-to-end training / inference pipelines
    │   ├── __init__.py 
    │   ├── test_pipeline.py             
    │   └── train_pipeline.py   
    |
    ├── utils                   <- Helpers: logging, metrics, etc.
    │   ├── __init__.py 
    |   ├── model
    |   │   ├── __init__.py 
    |
    └── plots.py                <- Code to create visualizations
```

--------

