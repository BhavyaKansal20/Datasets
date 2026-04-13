<div align="center">

![Datasets Banner](banner.png)

<br/>

---

# 📊 Bhavya Kansal - Dataset Repository

***Curated CSV datasets for machine learning, analytics, and educational workflows***

![Datasets](https://img.shields.io/badge/Datasets-26-0B7285?style=for-the-badge) ![Format](https://img.shields.io/badge/Format-CSV-1C7ED6?style=for-the-badge) ![Total Size](https://img.shields.io/badge/Total_Size-4.02_MB-2F9E44?style=for-the-badge) ![Updated](https://img.shields.io/badge/Updated-Apr_2026-F08C00?style=for-the-badge)

</div>

---

## **Overview**

***My Datasets Repository*** contains practical CSV files for:

- Machine learning model training
- EDA and feature engineering
- Classification and regression practice
- Academic projects and interview preparation

**Maintainer:** Bhavya Kansal  
**Portfolio:** https://bhavyakansal.dev  
**GitHub:** https://github.com/BhavyaKansal20

---

## **Repository Snapshot**

| Metric | Value |
|---|---:|
| Total datasets | 26 |
| File format | CSV |
| Approx. storage | 4.02 MB |
| Largest dataset | House Prices.csv |
| Smallest dataset | Placement2.csv |

---

## **Want To Download Any CSV For Local Use?**

Follow these steps:

<ol>
  <li>Open any CSV file in this repository</li>
  <li>Click the <b>Raw</b> button (top-right above file preview)</li>
  <li>Copy the URL of that raw file</li>
  <li>Create a local folder on your desktop</li>
  <li>Create a Python file inside that folder</li>
  <li>Paste the script below and run it</li>
  <li>The CSV will be downloaded locally</li>
</ol>

```python
import requests
import pandas as pd

url = "{paste_raw_url_here}"
res = requests.get(url, allow_redirects=True)

with open("download_file_name.csv", "wb") as file:
    file.write(res.content)

download_file_name = pd.read_csv("download_file_name.csv")
print(download_file_name.head())
```

---

## **Full Dataset Catalog**

| Dataset | Rows | Columns | Size (KB) | Primary Use |
|---|---:|---:|---:|---|
| Boston.csv | 506 | 15 | 36.8 | Regression |
| Crop.csv | 620 | 12 | 38.4 | Classification |
| DBSCAN_DATA.csv | 500 | 2 | 18.0 | Clustering |
| House Prices.csv | 21613 | 21 | 2190.0 | Pricing Regression |
| Placement2.csv | 100 | 3 | 1.0 | Placement Classification |
| Salary Data.csv | 375 | 6 | 18.9 | Salary Regression |
| Salary.csv | 375 | 3 | 4.8 | Salary Regression |
| Social_Network_Ads.csv | 400 | 5 | 10.7 | Binary Classification |
| Titanic-Dataset.csv | 891 | 12 | 59.8 | Survival Classification |
| bitcoin.csv | 2785 | 7 | 180.7 | Time Series Analysis |
| breast-cancer.csv | 569 | 32 | 121.7 | Medical Classification |
| car data.csv | 301 | 9 | 16.8 | Price Prediction |
| car.csv | 301 | 9 | 16.8 | Price Prediction |
| diabetes.csv | 768 | 9 | 22.6 | Medical Classification |
| houseprice.csv | 21613 | 13 | 1008.5 | House Price Regression |
| iris copy.csv | 150 | 5 | 4.6 | Multiclass Classification |
| iris.csv | 150 | 5 | 4.6 | Multiclass Classification |
| loan.csv | 614 | 13 | 37.1 | Loan Risk Classification |
| medical_data.csv | 4240 | 16 | 187.3 | Healthcare Analytics |
| placement.csv | 200 | 2 | 2.1 | Placement Insights |
| polynomial.csv | 200 | 2 | 2.1 | Curve Fitting |
| polynomial1.csv | 200 | 2 | 2.1 | Curve Fitting |
| polynomial2.csv | 200 | 2 | 2.1 | Curve Fitting |
| polynomial_classification.csv | 10000 | 2 | 117.1 | Decision Boundary Classification |
| student_placement.csv | 1000 | 3 | 12.5 | Student Placement |
| unlabeled_iris.csv | 150 | 4 | 2.5 | Unsupervised Practice |

---

## **Dataset Source Links (For More Data)**

### **General ML Repositories**

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [Google Dataset Search](https://datasetsearch.research.google.com/)
- [OpenML](https://www.openml.org/)
- [Hugging Face Datasets](https://huggingface.co/datasets)
- [Papers with Code - Datasets](https://paperswithcode.com/datasets)
- [Zenodo](https://zenodo.org/)
- [Data World](https://data.world/)
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)

---

### **Government and Open Data Portals**

- [India AI Datasets](https://indiaai.gov.in/datasets)
- [Data.gov.in](https://data.gov.in/)
- [Data.gov (USA)](https://data.gov/)
- [EU Open Data Portal](https://data.europa.eu/en)
- [Canada Open Government](https://open.canada.ca/en/open-data)
- [Australia Data Portal](https://data.gov.au/)

---

### **Domain-Specific Sources**

- [COCO Dataset](https://cocodataset.org/)
- [ImageNet](http://www.image-net.org/)
- [Common Crawl](https://commoncrawl.org/)
- [Project Gutenberg](https://www.gutenberg.org/)
- [PhysioNet](https://physionet.org/)
- [MIMIC-III](https://mimic.physionet.org/)
- [OpenSLR](https://www.openslr.org/)
- [OpenStreetMap (Geofabrik)](https://download.geofabrik.de/)

---

### **Quick Access Table**

| Name | Domain | Link |
|---|---|---|
| UCI ML Repo | General | [Open](https://archive.ics.uci.edu/) |
| Kaggle | General | [Open](https://www.kaggle.com/datasets) |
| IndiaAI | Govt (India) | [Open](https://indiaai.gov.in/datasets) |
| Data.gov.in | Govt (India) | [Open](https://data.gov.in/) |
| Data.gov | Govt (USA) | [Open](https://data.gov/) |
| Hugging Face | NLP/ML | [Open](https://huggingface.co/datasets) |
| Papers with Code | Benchmarks | [Open](https://paperswithcode.com/datasets) |
| Zenodo | Research | [Open](https://zenodo.org/) |

---

## **Usage**

These datasets can be used for:

- Machine learning projects
- Data analysis and visualization
- Educational and tutorial workflows

---

## **Contributing**

If you want to add more datasets, open a PR and include:

- File name
- Small description
- Source/reference (if public)
- Intended use case

---

## **License and Compliance**

This repository uses the BSD-2-Clause license. See LICENSE for complete terms.

---

***Important:*** If any dataset comes from an external source, follow its original license and attribution requirements.

---

## **Contact**

- Website: https://bhavyakansal.dev
- GitHub: https://github.com/BhavyaKansal20

If this repository helped you, consider starring ⭐️ it.
