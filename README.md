end-to-end-data-science-project
==============================

The project goes through the process of completting an end to end Data Science project, starting with a problem statement and end with a deployed product that our client will be able to use.

Table of Content
-------
1. Problem statement
2. Business Case
3. Pick a proper Dataset
4. Structure DS Project
5. Data Exploration
6. Data Preprocessing
7. Data Analytics
8. Feature Engineering
9. ML Model Training

More in-details
---------------
### 1. Problem statement
A (fictional) client is an IT educational institute They have reached out to us with the following:
“IT jobs and technologies keep evolving quickly This makes our field to be one of the most interesting out there But on the other hand, such fast development confuses our
students They do not know which job profile is most related to the skills they already have or want to learn.“

“Do I need to learn C++ to be a Data Scientist? Do DevOps and System admins use the same technologies? I really like JavaScript can I use it in Data Analytics?”

Those are some of the questions that our students ask Could you please develop a data driven solution for our students to answer such questions? They mostly want to understand the relationships between the jobs and the technologies.

#### Possible solutions
1. Cluster most-related job profiles into groups.
2. Recommender ML model to recommend certain job profile based on a given skills/programing languages/framworks.

### 2. Business Case
What are the KPIs that you will positively impact?
1. Higher enrollment rate due to the higher certainty.
2. Decrease in drop out rate.
3. Time saved for the academic advisors.

### 3. Pick a proper Dataset
If you want data about IT job profiles, programming languages, and frameworks, the first place to look for such dataset is for sure stack overflow, so we will be using <a target="_blank" href="https://insights.stackoverflow.com/survey/2020"> Stack Overflow Annual Developer Survey 2020</a>. [<a target="_blank" href="https://drive.google.com/file/d/1dfGerWeWkcyQ9GX9x20rdSGj7WtEpzBB/view"> Download Dataset</a>]

### 4. Structure DS Project

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
        
### Data Prepration & Modeling (from point 5 to 9)
All details are in 5 different notebooks in the following directory ```end-to-end-data-science-project/notebooks```

Resource 
--------
* <a target="_blank" href="https://www.youtube.com/watch?v=lULf9VKIA4o&list=PLatl6hdtJ0RkUSCChqOAVhnv5juWaoAyK"> Data science end-to-end project from preparation to production playlist by Deena Gergis</a>
* <a target="_blank" href="https://github.com/Deena-Gergis/e2e_ds_project"> Original GitHub Repo by Deena Gergis</a>
* <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">Cookiecutter data science project template</a>
* <a target="_blank" href="https://www.youtube.com/watch?v=NEaUSP4YerM"> TSNE explaination by StatQuest </a>
