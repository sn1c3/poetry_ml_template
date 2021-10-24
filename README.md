# Template
Created this template to make machine learning projects more structured. 
As a reference I based my template on the [cookiecutter-data-science structure](https://github.com/drivendata/cookiecutter-data-science).

# Setup Project
1. Install python-poetry (https://python-poetry.org/docs/#installation)
2. Execute the setup.sh-file<br>
`bash setup.sh`
# Folder structure
```
|-- data/                   
    |-- raw/                <-  The original, immutable data dump.
    |-- processed/          <-  The final, canonical data sets for modeling.
|-- documentation/          <-  Textual documentation
|-- notebooks/              <-  Trained and serialized models, model predictions, or model summaries
|-- models/                 <-  Jupyter notebooks. Naming convention is a number (for ordering),
│                               the creator's initials, and a short `-` delimited description, e.g.
│                               `1.0-jqp-initial-data-exploration`.
|-- src/                    <-  Source code for use in this project.
    |-- config.py           <-  Set environment variables.
|-- add-jupyter-venv.sh     <-  Adds virtualenv to ipykernel.
|-- pyproject.toml          <-  Installs project and sets up environment.
|-- .gitignore              <-  gitignore.
```