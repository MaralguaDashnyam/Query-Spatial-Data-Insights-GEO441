# Query Spatial Data for New Insights

👩‍💻 by Hera Dashnyam | 📍 Miami University  
🗓️ February–March 2025  

This project uses **ArcGIS Pro** and **Census-based shapefiles** to query, join, and visualize U.S. spatial data.  
It focuses on two geospatial problems:

---

## Project Highlights

### 1. High Old/Young Ratios by U.S. County  
- Computed the **Age Index** (65+ vs <21) using U.S. Census 2000 data  
- Created a **choropleth map** of the contiguous U.S.  
- Highlighted counties with disproportionately older populations  

📍 Featured Counties:  
Florida – Collier, Lee, Sarasota, etc.  
Massachusetts – Barnstable  
Arizona – Yavapai

![Age Index Map](https://drive.google.com/uc?export=view&id=1sodM_fm2JKpDIeHrVNSEhK0ZRv2K8h2P)

---

### 2. Soil Fertility Mapping – Macon County, NC  
- Joined two shapefiles using a common key (BLKGRP)  
- Mapped **Fertility Class (1–5)** and soil drainage characteristics  
- Designed clear legends, color schemes, and map elements

![Soil Fertility Map](https://drive.google.com/uc?export=view&id=18qRf2xLnRZ5Je_WeS0ofamHOlG7Qw73M)

---

## Data Operations

- Table joins (shapefile + DBF)  
- Age Index calculation and classification  
- Query filtering (e.g., HHINCOME < $30K)  
- Field mapping and symbology setup  
- Statistical breakdown via attribute tables

---

## Tools Used

- ArcGIS Pro  
- Google Colab (.ipynb formatting)  
- U.S. Census shapefiles (2000)  
- Geospatial query and map design workflows  

---

## 🔗 View in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wItiUkFvQdmpnEsguL3YiJXtmmZCbqfE?usp=sharing)

---

## Repository Contents

- `Query_Spatial_Data_Insights.ipynb` – Main notebook
- `OldYoung_Map.png` – Population map
- `SoilFertility_Map.png` – Fertility classification
- `README.md` – Project overview

---

## License

MIT © Hera Dashnyam
