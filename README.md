# Baseics Projects

A home for reproducible data science projects, notebooks, and analysis notes.

## Start a project

1. Create a folder under `projects/` using the project template.
2. Copy `notebooks/01_data_science_project_template.ipynb` into the project folder.
3. Keep raw and local data in `data/`; it is ignored by Git.
4. Save shareable figures and tables in `outputs/`; add selected final assets to the portfolio repository.
5. Run the notebook from top to bottom before committing.

## Local setup

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m ipykernel install --user --name baseics-projects --display-name "Python (Baseics Projects)"
jupyter lab
```

In VS Code, select the `Python (Baseics Projects)` kernel for each notebook.

## Publish a project

The source notebook and project notes belong here. A polished summary, selected charts, and a link back to the source repository belong in `TejasPortfolio.github.io/data-science/`.

```bash
git add .
git commit -m "Add <project name> analysis"
git push
```
