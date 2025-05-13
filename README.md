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
