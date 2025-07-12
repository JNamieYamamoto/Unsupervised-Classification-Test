# Unsupervised Classification of Urban Street Networks in São Paulo State (FIRST DRAFT)
**⚠️ Note: This is a preliminary/first draft of my final project.**  
The content, structure, and implementation are subject to significant changes as development progresses.

**Focus:** Street networks across São Paulo state  
**⚠️ Status:** Learning project, so methods and organization are evolving  :)

## 📌 Quick Overview
- **Data**: Street networks from OpenStreetMap (via 'OSMnx')
- **Metrics**: ['k_avg', 
                'edge_length_avg', 
                'streets_per_node_avg', 
                'street_length_avg',
                'circuity_avg', 
                'node_density_km', 
                'intersection_density_km', 
                'edge_density_km', 
                'street_density_km']
- **Clustering Methods**:
  - K-means
  - DBSCAN 
  - Agglomerative
  - Mean Shift
- **Goal**: Compare clustering approaches for urban morphology classification
  
## Install requirements:
   ```bash
   pip install osmnx networkx scikit-learn pandas matplotlib
