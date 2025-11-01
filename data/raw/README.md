# Data Directory

This folder contains the datasets used in the *Clustering Seismic Events* project.

---

## 📂 Structure
data/
├── raw/ # Original raw data (not modified)

---

## 🌍 Data Source
The main dataset (`all_week.csv`) was obtained from the **USGS Earthquake Hazards Program** API:
> https://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php

This dataset includes:
- `time`
- `latitude`, 
- `longitude`,
- `depth`,
- `mag`,
- `magtype`,
- `nst`,
- `gap`,
- `dmin`,
- `rms`,
- `net`, 
- `id`,
- `update`,
- `place`,
- `type`,
- `locationsource`,
- `magsource`,
- `horizontalerror`,
- `deptherror`,
- `magerror`,
- `magnst`,
- `status`

---

## ⚙️ Usage
- Place the raw file (`all_week.csv`) inside `data/raw/`.
- Do **not** modify the raw data directly.  
  Any preprocessing or feature engineering should be done via scripts or notebooks, saving results into `data/processed/`.

---

## ⚠️ Git Policy
Raw and large datasets are excluded from version control via `.gitignore`.  
Only lightweight or illustrative samples should be committed if necessary.