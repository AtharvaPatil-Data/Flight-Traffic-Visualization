# Raw Data – Flight Traffic Trends Project

This folder is intended for storing the **original, unprocessed dataset** used in the *Visualizing Flight Traffic Trends* project.

---

## 📂 Dataset Source
- **Title:** Airline Delay Analysis  
- **Provider:** Kaggle  
- **Link:** [Airline Delay Analysis Dataset](https://www.kaggle.com/datasets/sherrytp/airline-delay-analysis)  
- **Size:** ~9 GB (12 CSV files, 2009–2020)  
- **Records:** ~69 million after combining all files  
- **Attributes:** Flight delays, routes, origins/destinations, cancellations, diversions, operational data, and more.

---

## 📜 Notes
- The dataset is **not included** in this repository due to GitHub’s file size limitations.  
- Please download the dataset directly from Kaggle using the link above.  
- Once downloaded, extract and place the files into this `/data/raw/` folder before running any processing scripts or notebooks.

---

## 🔧 Usage
Example (Google Colab):
```python
from google.colab import drive
drive.mount('/content/drive')

DATA_DIR = "/content/drive/MyDrive/airline-delay-analysis/"
