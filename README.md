# INST414

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Analyzing audience and cinephile reception, this project examines how visual and thematic elements influence the ratings of auteur-driven films across Criterion, IMDb, and Letterboxd, balancing artistic significance with broader audience trends.

# Exploring Auteur Theory with Quantitative Methods  
### Audience and Cinephile Reception of Criterion Films  

## **Project Overview**  
This research examines how auteur-driven films are perceived differently by cinephiles versus broader audiences. Using **Criterion Collection metadata, Letterboxd ratings, and IMDb data**, the project integrates quantitative analysis, sentiment trends, and clustering techniques to explore rating disparities, thematic correlations, and stylistic patterns.  

## **Dependencies**  
To run this project, ensure you have the following installed:  
- Python 3.10+  
- Conda or virtualenv for environment management  
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- NLTK or spaCy for NLP analysis  
- curl & wget (for data acquisition)  
- Jupyter Notebook for exploration  

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
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
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         auteur_theory and configuration for tools like black
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
└── auteur_theory   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes auteur_theory a Python module
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

