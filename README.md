# Movies and Audience Ratings - Daniel Yarritu
BAN 6003 semester project, created from [the professor's Option 1 template](https://github.com/tianhaiz/ban6003-project-option-1-movies-template).

## Current submission — Milestone 2

Open [the project notebook](notebooks/movies_project_starter.ipynb) for the Milestone 1 profile and Milestone 2 cleaning, aggregation, joins, and DuckDB validation. The [preliminary ABT](outputs/movies_preliminary_abt.csv) has one row per movie and uses `movieId` as its key. The notebook ends with the AI Use Disclosure.

## Reproduce
All five supplied raw CSV files are included in `data/`; do not edit them. Open this repository in GitHub Codespaces and wait for setup, or install `requirements.txt` in your Python environment. From the repository root run:

```bash
python -m jupyter nbconvert --execute --to notebook --inplace notebooks/movies_project_starter.ipynb
```

The notebook detects execution from the root or `notebooks/`. `outputs/` contains column profiles, key/value checks, and raw-file SHA-256 hashes. The notebook recreates the preliminary ABT on each run. DuckDB runs locally on the rating events without credentials. See `data/README.md` for raw-table grain and join guidance.
