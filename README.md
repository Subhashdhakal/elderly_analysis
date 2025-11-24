# Elderly Vulnerability Analysis – Nepal (Census 2021)
# Elderly Vulnerability Analysis – Nepal (Census 2021)

This repository contains the full workflow, analysis scripts, datasets, and interactive visualizations used in the project:

**“District-Level Elderly Vulnerability in Nepal using Census 2021 Data.”**

The analysis integrates demographic, economic, migration, and infrastructure indicators to construct a composite vulnerability index for all 77 districts. Interactive dashboards and visual tools are provided to support policymakers, researchers, and development partners.

---

## 🌐 Interactive Visualizations (GitHub Pages)

All interactive charts are publicly accessible via GitHub Pages:

### **1. Elderly % vs Vulnerability (Scatter Plot)**
👉 https://subhashdhakal.github.io/elderly_analysis/outputs/figures/interactive_scatter.html

### **2. Top 20 Districts by Dimension**
👉 https://subhashdhakal.github.io/elderly_analysis/outputs/figures/interactive_top20.html

### **3. Parallel Coordinates Plot**
👉 https://subhashdhakal.github.io/elderly_analysis/outputs/figures/interactive_parallel.html

### **4. Vulnerability by Province (Boxplot)**
👉 https://subhashdhakal.github.io/elderly_analysis/outputs/figures/interactive_boxplot.html

### **5. Sunburst – Hierarchical Risk Distribution**
👉 https://subhashdhakal.github.io/elderly_analysis/outputs/figures/interactive_sunburst.html

### **6. 3D Vulnerability Space**
👉 https://subhashdhakal.github.io/elderly_analysis/outputs/figures/interactive_3d.html

### **7. Multi-Panel Dashboard**
👉 https://subhashdhakal.github.io/elderly_analysis/interactive_dashboard.html

---

## 📁 Repository Structure

elderly_analysis/
│
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for exploration & modeling
├── scripts/ # Python scripts for computation and cleaning
├── visuals/ # Static plots (PNG/JPG)
├── interactive/ # HTML-based interactive visualizations
├── results/ # Ranking tables, cluster outputs
└── README.md
---
---

## 🧠 Methodological Overview

- **Data Source:** Nepal Census 2021 (CBS)
- **Framework:** Multi-dimensional vulnerability model  
- **Indicators:** Demographic, economic, migration, infrastructure  
- **Analysis:**  
  - K-means clustering (k=5)  
  - ANOVA + silhouette validation  
  - Sensitivity checks  
  - Province and district-level comparisons  
- **Tools:** Python (Pandas, GeoPandas, Plotly), Jupyter, QGIS

---

## 🎯 Purpose

- Identify **district-level vulnerability hotspots**  
- Support **evidence-based ageing policies** in Nepal  
- Provide tools for **provincial and local planning**  
- Demonstrate use of **interactive visualizations** for data transparency  

---

## 📬 Contact

Author: **Subhash Sagar Mahesh Dhakal**  
Email: *subhashdhakal15@gmail.com*  

