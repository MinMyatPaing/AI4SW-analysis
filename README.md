# AI4SW Graphs: Task Analysis and Visualization

This project analyzes and visualizes user task data for the AI4SW project using Jupyter notebooks and Python data science libraries. It includes scripts for filtering, ordering, and plotting user task completion data, ensuring consistency with a reference user list.

## Project Structure

- `Task 1/` — Analysis and plots for Task 1
  - `main.ipynb` — Main notebook for Task 1
  - `TSDA8-constant-data.csv` — Reference user list (constant data)
  - `TSDA8-daily-data-filtered.csv` — Daily task data
- `Task 2/` — Analysis and plots for Task 2
- `Task 3/` — Analysis and plots for Task 3
- `Year of Study Table/` — Year of study analysis
- `requirements.txt` — Python dependencies
- `environment.yml` — Conda environment file (optional)

## Setup Instructions

### Request Files from Min (u2289897) and Omar (u2289896)

### 1. Clone the Repository

```sh
git clone <your-repo-url>
cd "AI4SW graphs"
```

### 2. Set Up the Python Environment

#### Option A: Using Conda (Recommended)

Create a new environment from the provided `environment.yml`:

```sh
conda env create -f environment.yml
conda activate ai4sw-graphs
```

#### Option B: Using pip

Create a virtual environment (optional but recommended):

```sh
python3 -m venv env
source env/bin/activate
```

Install dependencies:

```sh
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```sh
jupyter notebook
```

Open the relevant notebook (e.g., `Task 1/main.ipynb`) in your browser.

## Usage

- Run all cells in the notebook to generate the analysis and plots.
- Ensure the CSV data files are present in the same directory as the notebook.
- The code will automatically filter and order users based on the constant data file.

## Technologies Used

- Python 3
- pandas
- matplotlib
- numpy
- Jupyter Notebook

## Environment File Generation

To generate a new `environment.yml` from your current environment, run:

```sh
conda env export --from-history > environment.yml
```

## Notes

- If you encounter issues with missing packages, ensure your environment matches the dependencies in `requirements.txt` or `environment.yml`.
- For any questions or issues, please contact the project maintainer.
