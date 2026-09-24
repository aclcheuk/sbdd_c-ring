# Notes for SBDD Project

## Set Up
### Setting up Environment
1) Make `environments.yml` file
2) Install mamba using `conda install conda-forge::mamba`
3) Create venv: `mamba env create -f environment.yml`
4) Activate venv: `mamba activate sbdd-cring-project`
5) Freeze this build: `mamba env export --no-builds > environment_freeze.yml`
6) Create `.gitignore` file
7) `git init`, `git add .`
8) `git commit -m "Initial commit: Set up environment and folder structure"`

### Organise Directory
- `README.md`
- `data` folder - raw, processed
- `notebooks` folder
- `results` folder
- `images` folder 