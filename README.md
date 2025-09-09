# PROG-8431 Workshop 1

## Overview
This repository holds the material for Workshop 1 of PROG-8431. The main artifact is a Jupyter notebook named `workshop1.ipynb`. Use the notebook to follow the steps, run examples, and answer the questions for the lab. The repo also includes a `.gitignore` file to keep local files out of version control.

## Goals
- Open the notebook and run all cells end to end.
- Complete the required exercises inside the notebook.
- Save your answers in the notebook before submission.
- Use version control to track your progress.

## Requirements
- Python 3.10 or newer
- JupyterLab or Jupyter Notebook
- Common data packages: numpy, pandas
- Optional packages you might need: matplotlib, scikit-learn, seaborn

## Quick Start
1. Create an isolated environment  
   - Conda:  
     ```bash
     conda create -n prog8431 python=3.10
     conda activate prog8431
     ```  
   - venv:  
     ```bash
     python -m venv .venv
     # Activate:
     # Windows: .venv\Scripts\activate
     # macOS/Linux: source .venv/bin/activate
     ```
2. Install tools  
   ```bash
   pip install jupyterlab numpy pandas matplotlib scikit-learn seaborn
   ```
3. Launch Jupyter  
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```
4. Open `workshop1.ipynb`.
5. Run cells in order. Use “Restart Kernel and Run All” to confirm a clean run.

## Repo Structure
- `workshop1.ipynb`: the lab notebook with instructions and cells to run.
- `.gitignore`: default ignores for local artifacts.

## How to Work in the Notebook
- Read the cell above before you run the next one.
- Run a single cell with `Shift+Enter`.
- Restart the kernel if variables collide or memory errors occur.
- Keep code, outputs, and short notes in the notebook so grading is simple.

## Data Handling
- Place small CSV files in a local `data/` folder at the repo root if required.
- Do not commit large files. Use Git LFS or external storage if needed.
- Use relative paths when loading data, for example: `data/your_file.csv`.

## Tips
- Use a clean environment so package versions do not conflict.
- If a plot does not show, add `%matplotlib inline` at the top of a cell.
- Adjust pandas display settings if needed:
  ```python
  import pandas as pd
  pd.set_option("display.max_rows", 100)
  pd.set_option("display.max_columns", 100)
  ```

## Common Issues
- **Package not found**: run `pip install the_missing_package`.
- **Kernel dies or RAM issues**: close other apps, restart the kernel, run sequentially.
- **Different outputs across runs**: restart the kernel and run all cells again.

## Version Control
- Clone:  
  ```bash
  git clone https://github.com/elopezcs/PROG-8431-workshop1
  ```
- Create a branch:  
  ```bash
  git checkout -b workshop1-solutions
  ```
- Commit:  
  ```bash
  git add -A
  git commit -m "Finish section X"
  ```
- Push:  
  ```bash
  git push -u origin workshop1-solutions
  ```

## Submission
- Ensure the notebook runs start to finish without errors.
- Save and keep outputs visible unless instructed otherwise.
- Name duplicates clearly, for example: `workshop1_yourname.ipynb`.
- Add a short note with your name, date, and course section if required.

## Code of Conduct
- Follow your institution’s academic integrity policy.
- Cite sources for any external code or text you adapt.

## License
If you plan to open source your solutions, add a LICENSE file (MIT is a common choice). If the course requires private submissions, keep the repo private.

## Contact
- Author or maintainer: Edwin López  
- Repository URL: [https://github.com/elopezcs/PROG-8431-workshop1](https://github.com/elopezcs/PROG-8431-workshop1)

## Changelog
- 2025-09-09: Initial README prepared.
