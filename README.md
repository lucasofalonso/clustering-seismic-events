# ML Seismic Clustering

This project applies KMeans model to cluster seismic events and further visualize them in a world map.


## ⚙️ Methods
- Data preprocessing with `pandas` and `scikit-learn`
- Standardization via `StandardScaler`
- Dimensionality reduction with `PCA`
- Clustering using `KMeans`
- Visualization with `matplotlib`, `plotly` and `folium`

---

## 🚀 How to Run
```bash
conda env create -f environment.yml
conda activate ml-seismic-clustering
python -m ipykernel install --user --name ml-seismic-clustering

