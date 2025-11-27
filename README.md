
# Claims Data Analysis

## Project Overview

This project analyzes healthcare claims data to identify billing patterns, common diagnoses and procedures, payer mix, and provider complexity. It simulates real-world tasks performed by healthcare data analysts.

## Repository Structure

claims-analysis/
├── data/                # CSV files (excluded via .gitignore)
├── notebooks/
└── claims_analysis.ipynb
├── requirements.txt
├── README.md
├── .gitignore

## Data Source

- Provided by course Module 6: `STONYBRK_20240531_HEADER.csv`, `STONYBRK_20240531_LINE.csv`, `STONYBRK_20240531_CODE.csv`.

## How to Run

1. Open `notebooks/claims_analysis.ipynb` in Google Colab
2. Install dependencies:

   ```bash
   pip install -r requirements.txt

pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0

1. **Create `.gitignore`** and include in requirements.txt

data/*.csv
pycache/
*.pyc
.ipynb_checkpoints/
.venv/
.env

3.**Push to GitHub**:

- Create repo `claims-analysis`.
- Add folders: `data/`, `notebooks/`.
- Upload notebook, README.md, requirements.txt, .gitignore.
- Commit and push.

4.**Double-check**:

- Notebook runs without errors.
- README is clear and professional.
- Repo structure matches assignment instructions.
