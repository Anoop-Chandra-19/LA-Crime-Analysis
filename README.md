# 📊 LA Crime Analysis

This notebook analyzes crime data from Los Angeles to identify patterns, visualize hot spots, and examine trends in different types of crime. It uses Python and geospatial tools for interactive, data-driven insights.

---

## 📁 Project Overview

Key objectives of the notebook:

- Clean and prepare LA crime datasets
- Handle missing or ambiguous values
- Identify top crime types and demographic trends
- Create geospatial heatmaps for different crime categories

---

## 🧰 Tools & Environment

This project is built and tested using:

- **Databricks Community Edition**
- Python (Databricks Runtime)
- Libraries: `pandas`, `seaborn`, `matplotlib`, `folium`

---

## 🚀 How to Run This Notebook (on Databricks Community Edition)

### Step 1: Sign up / Log in to Databricks CE

- Go to [https://community.cloud.databricks.com](https://community.cloud.databricks.com)
- Log in or sign up for a free account.

---

### Step 2: Create a New Workspace and Cluster

1. Click **Compute** on the sidebar → **Create Cluster**
2. Name your cluster (e.g., `la-crime-cluster`)
3. Choose the latest **Databricks Runtime** (Python)
4. Click **Create Cluster**
5. Wait until the cluster status is **Running**

---

### Step 3: Import the Notebook

1. Go to **Workspace** in the sidebar
2. Click the dropdown next to your folder → **Import**
3. Choose **Import from File**
4. Upload `LA Crime Analysis Final.ipynb`

---

### Step 4: Upload All 11 Dataset Files

1. Go to **Data** on the sidebar → **Add Data**
2. Click **Upload File**
3. Select **all 11 CSV files** (hold Shift/Ctrl to select multiple)
4. After uploading, Databricks will show the file paths, typically like this:
   ```
   /dbfs/FileStore/tables/crime_data_part1.csv
   /dbfs/FileStore/tables/crime_data_part2.csv
   ...
   /dbfs/FileStore/tables/crime_data_part11.csv
   ```
5. Use these paths in your notebook when merging the data

📌 *Note: The notebook already handles merging the 11 parts into one dataset.*

---

### Step 5: Attach Notebook to the Cluster

- Open the notebook
- From the top dropdown, attach it to your cluster

---

### Step 6: Run the Notebook

- Click **Run All** or run cells step-by-step
- Visualizations and maps will render inside the notebook

---

## 📌 Outputs

- Top 10 crime categories
- Victim age and gender distributions
- Yearly and monthly crime counts
- **Interactive Folium heatmaps**:
  - All crimes (2021)
  - Stolen vehicles
  - Battery
  - Intimate partner assault

---

## 🗂️ File Structure

```
├── LA Crime Analysis Final.ipynb     # Main notebook
├── README.md                         # This file
└── /data                             # Upload 11 CSV files here
```
