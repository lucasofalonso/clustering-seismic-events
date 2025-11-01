# Reports Directory

This folder stores the outputs and documentation generated during the *Clustering Seismic Events* project.

---

## 📂 Structure

reports/
├── maps/ # Interactive maps (e.g., cluster_map.html)
└── instructions.pdf # Mini-guide describing the methodology and results


---

## 📄 Included Documents

- **`cluster_map.html`** — interactive Folium map showing clustered seismic events on a world map.  
  Each cluster is color-coded for spatial exploration of earthquake patterns.

- **`instructions.pdf`** — concise technical report detailing the methodology, from data preprocessing to PCA dimensionality reduction and K-Means clustering.  
  It also discusses the rationale for choosing seven clusters and provides physical interpretations of the patterns found.

---

## ⚙️ Usage
- Reports and figures are generated automatically by the analysis notebooks or scripts.  
- The PDF can be read directly as a methodological summary of the project.

---

## ⚠️ Git Policy
Only representative reports (e.g., `instructions.pdf`, example maps) should be versioned.  
Large temporary or auto-generated files remain excluded through `.gitignore`.
