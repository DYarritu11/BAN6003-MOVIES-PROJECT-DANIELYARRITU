# Movies and Audience Ratings - Daniel Yarritu
BAN 6003 semester project, created from [the professor's Option 1 template](https://github.com/tianhaiz/ban6003-project-option-1-movies-template).

## Current submission: Milestone 1
Open `notebooks/movies_project_starter.ipynb`. It contains the business framing, executed profiles, interpreted quality findings, cleaning plan, candidate outcome, and ethics/governance notes. Later milestone examples are preserved behind `RUN_FUTURE_MILESTONES = False` and are not completed work.

## Reproduce
All five supplied raw CSV files are included in `data/`; do not edit them. Open this repository in GitHub Codespaces and wait for setup, or install `requirements.txt` in your Python environment. From the repository root run:

```bash
python -m jupyter nbconvert --execute --to notebook --inplace notebooks/movies_project_starter.ipynb
python -m jupyter nbconvert --to html --output movies_milestone1 --output-dir reports notebooks/movies_project_starter.ipynb
```

The notebook detects execution from the root or `notebooks/`. `outputs/` contains column profiles, key/value checks, and raw-file SHA-256 hashes. The final ABT, data dictionary, model, and presentation will be completed in later milestones. See `data/README.md` for raw-table grain and join guidance.
