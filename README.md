# Datship-Development-Template
Template repository for DataShip project development structure

```
├── data/
├── notebooks/
├── outputs/
├── scripts/
├── temp_files/
├── README.md
└── how_to_connect_to_project_git_repo.ipynb
```

### 1. **data/**
- **Purpose:** Stores all raw, intermediate, and cleaned datasets.
- **Content:**
  - `raw/` – Unprocessed data files directly imported from data sources.
  - `processed/` – Data files that have undergone initial cleaning or transformation.
  - `cleaned/` - Data that is fully cleaned and can delivered to stakeholder at Dataship

### 2. **notebooks/**
- **Purpose:** Notebook-based development, EDA, and data visualization.
- **Content:**
  - Jupyter or Google Collab Notebooks for data exploration and analysis.
  - Naming convention: `eda.ipynb`, `data_cleaning.ipynb`, `kpi_calculation.ipynb`.

### 3. **outputs/**
- **Purpose:** Stores final deliverables such as CSVs, images, and reports.
- **Content:**
  - `figures/` – Visualizations and plots.
  - `reports/` – Final reports, summarized datasets.
  - `exports/` – Exported files for integration with dashboards or other applications.

### 4. **scripts/**
- **Purpose:** Python scripts for data processing and automation.
- **Content:**
  - `data_extraction.py` – Data extraction from APIs or databases.
  - `data_cleaning.py` – Data cleaning and preprocessing.
  - `data_transformation.py` – Data transformation and feature engineering.
  - `kpi_calculation.py` – KPI calculations.

### 5. **temp_files/**
- **Purpose:** Working directory for intermediary files generated during processing.
- **Content:** Temporary CSVs, logs, or checkpoint files that can be deleted after project completion.

### 6. **README.md**
- **Purpose:** Overview of the project, folder structure, and setup instructions.

## ✅ Project Setup Checklist
1. **Clone the repository in `01 - DEVELOPMENT` to setup the folder structure:**
2. **Store raw data in the `data` folder.**
3. **Use the `scripts` folder for data processing scripts.**
4. **Store intermediate and final outputs in the `outputs` folder.**
5. **Use the `temp_files` folder for temporary data or scratch files.**
6. **Move final deliverables to `00 - FINAL DELIVERABLE`.**

## 🛠️ Development Guidelines
- Store raw and cleaned data in `01 - DEVELOPMENT/Data`.
- Develop and test notebooks in the `notebooks` folder.
- Store all final outputs in the `outputs` folder.
- Keep processing scripts organized in the `scripts` folder.
- Use the `temp_files` folder for scratch files or intermediary data that can be deleted.
- Include instructions for how stakeholder can clone/connet to repository `how_to_connect_to_project_git_repo.ipynb`.
- Use Jupyter Notebooks/notebooks of choice or Python scripts for data processing in `01 - DEVELOPMENT/Notebooks`.
- Scripts should follow naming conventions: `data_extraction.py`, `data_cleaning.py`, etc.
- Ensure that all code is well-documented and includes error handling.
- Keep the `00 - FINAL DELIVERABLE` folder in the main repository clean and only for final outputs.

## 🚀 Deployment and Handoff
- Move all final deliverables to `00 - FINAL DELIVERABLE`.
- Include a final presentation in `00 - FINAL DELIVERABLE/Presentations`.
- Record a Loom video summarizing the project and store it in `00 - FINAL DELIVERABLE`.

