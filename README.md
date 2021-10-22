# Folder structure
|-- data/                   
    |-- raw/                <-  The original, immutable data dump.
    |-- processed/          <-  The final, canonical data sets for modeling.
|-- notebooks/              <-  Trained and serialized models, model predictions, or model summaries
|-- models/                 <-  Jupyter notebooks. Naming convention is a number (for ordering),
│                               the creator's initials, and a short `-` delimited description, e.g.
│                               `1.0-jqp-initial-data-exploration`.
|-- src/                    <-  Source code for use in this project.
    |-- config.py           <-  Set environment variables.
|-- add-jupyter-venv.sh     <-  Adds virtualenv to ipykernel.
|-- pyproject.toml          <-  Installs project and sets up environment.
|-- .gitignore              <-  gitignore.