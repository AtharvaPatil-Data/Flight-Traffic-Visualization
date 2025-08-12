# Source Code – Flight Traffic Trends Project

This folder contains the **Google Colab notebook** used to process the raw airline delay dataset and prepare it for visualization.

---

## 📄 File
- **`flight_traffic_trends.ipynb`** – Colab notebook containing:
  - Data loading from Kaggle dataset (link in `data/raw/README.md`)
  - Data cleaning and filtering for years **2015–2019**
  - Route creation (`ORIGIN → DEST`)
  - Aggregation of total flight counts per route/year
  - Selection of **Top 5 busiest routes**
  - Export of a cleaned CSV for Tableau dashboarding

---

