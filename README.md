Task 5 — Exploratory Data Analysis (EDA)

**Dataset:** Iris (included as `iris_dataset.csv`)  
**Tools:** Python, pandas, matplotlib  
**Deliverables included in this folder:**
- `EDA_Iris.ipynb` — Jupyter Notebook with all steps and code
- `EDA_Report_Iris.pdf` — PDF report of plots and observations
- `iris_dataset.csv` — dataset used in the analysis

 How to Run
1. Download this folder.
2. Open `EDA_Iris.ipynb` in Jupyter (Anaconda or VS Code).
3. Run all cells. The notebook uses only pandas/matplotlib—no internet required.

Contents
- `.info()`, `.describe()`, `.value_counts()`
- Histograms, boxplots
- Correlation heatmap
- Scatter matrix (pairwise relationships)
- Key scatter plots by species
- Observations after each visual + final summary

Notes
- We avoided seaborn to ensure compatibility in restricted environments; matplotlib equivalents are used.
- Findings: petal-based features are most discriminative among species.
