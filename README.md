# 🚗 US Accidents - Exploratory Data Analysis

This project focuses on performing **Exploratory Data Analysis (EDA)** on the **US Accidents dataset** sourced from Kaggle. It involves loading, cleaning, and visualizing the data to uncover meaningful patterns and insights about road accidents in the United States.

---

## 📂 Dataset Info

- **Source**: [Kaggle - US Accidents (Sobhan Moosavi)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Size**: ~2.8 million records, 47 columns
- **Format**: CSV
- **Note**: Data **does not include New York (NY)**

### 🧾 What It Contains:
- Accident details (location, time, severity)
- Weather conditions
- Road attributes
- Temporal data (twilight phases, day/night, timestamps)

---

## 📦 Installation & Setup

```bash
pip install opendatasets --upgrade --quiet
python
Copy
Edit
import opendatasets as od
dataset_url = 'https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents'
od.download(dataset_url)
