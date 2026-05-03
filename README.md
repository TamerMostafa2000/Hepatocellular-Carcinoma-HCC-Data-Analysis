# Hepatocellular Carcinoma (HCC) Data Analysis 🏥

Exploratory Data Analysis (EDA) on real clinical data of patients diagnosed with Hepatocellular Carcinoma (HCC), sourced from a University Hospital in Portugal.

---

## 📌 Project Overview

Hepatocellular Carcinoma (HCC) is the most common form of liver cancer, accounting for 85–90% of all liver cancer cases. It is one of the most aggressive and difficult-to-treat malignancies worldwide.

This project performs in-depth exploratory analysis on clinical HCC data to uncover patterns in patient demographics, risk factors, and lab results — combining medical domain knowledge with data science techniques.

---

## 📊 Dataset

- **Source:** University Hospital in Portugal
- **Features:** 49 clinical features selected according to **EASL-EORTC Clinical Practice Guidelines**
- **Type:** Real patient data (demographic, risk factors, laboratory values, survival outcomes)

### Key Features Analyzed:
| Feature | Description |
|---|---|
| Age / Gender | Patient demographics |
| Nodule | Number of tumor nodules |
| Cirrhosis | Presence of liver cirrhosis |
| Alcohol | Alcohol consumption history |
| HCVAb | Hepatitis C virus antibody |
| AFP | Alpha-fetoprotein (tumor marker) |
| INR | International Normalized Ratio |
| Albumin, Creatinine, Hemoglobin | Key lab values |
| Packs_year | Smoking history |

---

## ⚙️ Project Pipeline

1. **Data Loading & Inspection** — understanding structure and data types
2. **Data Cleaning** — fixing comma/dot formatting issues in numeric columns, type conversion
3. **Missing Value Handling** — detecting and imputing missing data (median imputation)
4. **Outlier Detection** — using datasist library
5. **Feature Engineering** — converting binary codes to readable labels (Gender: 0/1 → Female/Male)
6. **Exploratory Data Analysis (EDA)** — visualizing distributions, risk factors, and clinical patterns

---

## 🔍 Key Findings

- **Males** are more frequently diagnosed with HCC than females
- **1 and 5 nodules** are the most common presentations
- **Alcoholism** is a notable risk factor — alcohol consumers show higher nodule counts
- Patients with **5 nodules** have higher average INR values, indicating worse liver function
- **Cirrhosis** and **HCV infection** appear as strong co-morbidities

---

## 🛠️ Libraries Used

```
pandas, numpy, seaborn, matplotlib, datasist
```

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
```bash
pip install pandas numpy seaborn matplotlib datasist
```
3. Open `HCC_data.ipynb` in Jupyter or Google Colab
4. Run all cells in order

---

## 👨‍💻 Author

**Tamer Mostafa** — Data Scientist | Medical Laboratory Specialist  
[GitHub](https://github.com/TamerMostafa2000)
