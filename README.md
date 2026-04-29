# Climate Challenge Week 0 – African Climate Trend Analysis

Analysis of historical climate data (2015-2026) for Ethiopia, Kenya, Sudan, Tanzania, Nigeria using NASA POWER data.

## Setup

1. Clone the repo
2. Create virtual environment: `python -m venv venv`
3. Activate: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Mac/Linux)
4. Install dependencies: `pip install -r requirements.txt`
5. Download the CSV files from the provided Google Drive and place them in a `data/` folder (do not commit them)

## Running the analysis

- Open `notebooks/ethiopia_eda.ipynb` and run all cells (repeat for each country)
- Then open `compare_countries.ipynb` and run all cells to generate cross-country comparison, vulnerability ranking, and COP32 insights

## Output

Cleaned CSV files saved to `data/` (excluded from git). Final report PDF submitted separately.

## CI

GitHub Actions runs `pip install -r requirements.txt` on each push.