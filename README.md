# HierarchiSense-CustomerAnalysis

# Mall Customer Segmentation Using Hierarchical Clustering

## Overview
This project performs **customer segmentation** using **hierarchical clustering techniques**, applying both **agglomerative (bottom‑up)** and **divisive (top‑down)** approaches to group mall customers based on their purchasing behavior.

The notebook focuses on understanding how different hierarchical strategies form customer segments and how dendrograms help interpret cluster structure.

## Dataset
Mall customer dataset with attributes including:
- Age
- Annual Income (k$)
- Spending Score (1–100)

For clustering analysis, the following features are used:
- **Annual Income**
- **Spending Score**

## Clustering Strategies Used

### 1️Agglomerative Hierarchical Clustering
- Starts with each customer as an individual cluster
- Iteratively merges the closest clusters
- Uses **Ward linkage** to minimize intra‑cluster variance
- Suitable for identifying compact and well‑separated clusters

### Divisive Hierarchical Clustering
- Starts with all customers in a single cluster
- Recursively splits clusters into smaller groups
- Helps observe how broad customer groups break down into sub‑segments

Both approaches are explored to understand different hierarchical perspectives on the same data.

## Dendrogram Analysis
- Dendrograms are plotted to visualize cluster formation
- Vertical distance is used to assess cluster separation
- A horizontal cut on the dendrogram is applied to determine the final clusters

### Final Cluster Selection
- Based on dendrogram interpretation, the data is segmented into:

**5 distinct customer clusters**

## Results & Visualization
- Customers are plotted in a 2D space:
  - X‑axis: Annual Income
  - Y‑axis: Spending Score
- Cluster labels from hierarchical clustering are visualized
- Distinct spending and income‑based customer groups are clearly visible

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit‑learn
- SciPy
- Jupyter Notebook

## How to Run
1. Clone the repository
2. Install dependencies:
   pip install pandas numpy matplotlib scikit-learn scipy
3. Open the notebook
4. Run cells sequentially to reproduce results

## Key Takeaway
This project demonstrates how **both agglomerative and divisive hierarchical clustering**, supported by dendrogram analysis, can be used to explore and interpret customer segmentation without predefined labels.
