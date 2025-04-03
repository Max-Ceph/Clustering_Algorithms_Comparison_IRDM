# Clustering_Algorithms_Comparison_IRDM

## 🧾 Project Overview

This notebook is part of the **IRDM Practical Assignment 1** and demonstrates the implementation and comparison of several clustering algorithms in Python using `scikit-learn`. The main focus is on understanding how different clustering techniques behave on synthetic datasets and how their performance can be evaluated.

---

## 🧠 Algorithms Implemented

1. **K-Means Clustering**
2. **Mini-Batch K-Means**
3. **Affinity Propagation**
4. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
5. **OPTICS**
6. **BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies)**
7. **Agglomerative Clustering**
8. **Mean-Shift Clustering**

Each algorithm is implemented with visualizations and short descriptions.

---

## 🧪 Evaluation Metrics

The following evaluation metrics were used to assess clustering quality:

- **Homogeneity Score**
- **Completeness Score**
- **V-Measure Score**

These metrics help determine how well the clusters correspond to ground truth classes.

---

## 📚 Technologies Used

- **Language**: Python  
- **Libraries**:  
  - `scikit-learn`  
  - `matplotlib`  
  - `numpy`  
  - `timeit` (for comparing runtime performance)

---

## 📁 Files

- `IRDM1prac.ipynb` – Main notebook with code and visualizations
- `IRDM1PracReport.docx` – Full report with background, code explanations, results and conclusions

---

## 📌 Key Learnings

- K-Means and Mini-Batch K-Means are fast and easy to use but require predefined cluster count.
- Affinity Propagation and DBSCAN do not require the number of clusters but are more sensitive to parameters.
- Mean-Shift is non-parametric but less scalable.
- BIRCH is suitable for large datasets but only works with numeric features.
- Clustering evaluation requires more than accuracy; metrics like homogeneity and v-measure are essential.

---

## 👤 Author

- **Maxim Azarnov**  
  Bachelor Student – Big Data Analysis  
  AITU, Kazakhstan  
  Email: 230101@astanait.edu.kz

---

## 📅 Coursework Info

- **Course**: Information Retrieval and Data Mining (IRDM)
- **Assignment**: Practical 1
- **Instructor**: *[Add if required]*
- **Term**: Spring 2025

---
