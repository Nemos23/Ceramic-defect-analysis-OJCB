# Ceramic-defect-analysis-OJCB

# 🏭 Reduce Manufacturing Defects Using SPC + Machine Learning

## 📌 Business Problem

A manufacturing plant is experiencing elevated defect rates, leading to increased scrap, rework, and production inefficiencies.

Despite having process data available, the plant lacks:

* Visibility into **root causes of defects**
* Statistical control over key variables
* A predictive system to **prevent defects before they occur**

---

## 🎯 Objective

Develop a data-driven framework to:

* Identify key drivers of defects
* Monitor process stability using **Statistical Process Control (SPC)**
* Predict defect occurrence based on process conditions
* Estimate potential reduction in defect rate

---

## 🧪 Dataset

This project uses the **Steel Plates Faults Dataset (UCI Machine Learning Repository)** as a proxy for industrial manufacturing defects.

Why this dataset?

* Represents **real-world industrial defect scenarios**
* Includes multiple process variables and defect classifications
* Highly analogous to ceramic and materials manufacturing environments

---

## 🛠️ Methodology

### 1. Exploratory Data Analysis (EDA)

* Distribution of defect types
* Correlation analysis between process variables
* Identification of abnormal patterns and outliers

### 2. Statistical Process Control (SPC)

* X̄-R control charts to monitor process stability
* Detection of:

  * Out-of-control points
  * Trends and shifts
* Process capability analysis:

  * Cp / Cpk evaluation

👉 Result: Identification of unstable process behavior driving defect variability

---

### 3. Defect Prediction Model

A machine learning model was developed to:

> Predict the probability of defect occurrence based on process variables

Models evaluated:

* Logistic Regression
* Random Forest (selected)

Evaluation metrics:

* Accuracy
* Precision / Recall
* Confusion Matrix

---

### 4. Feature Importance & Root Cause Analysis

* Identification of variables with highest impact on defects
* Translation of model outputs into **engineering insights**

Example:

* High variability in specific process parameters significantly increases defect probability

---

## 📊 Key Results

* Clear identification of **critical process variables affecting quality**
* Detection of **process instability periods** using SPC
* Predictive model capable of identifying high-risk conditions before defects occur

### 💡 Estimated Business Impact (Simulated Scenario)

* 📉 Defect rate reduction: **12–18%**
* 💰 Scrap cost reduction: **$30K–$60K annually**
* ⚙️ Improved process stability and consistency

---

## 🚀 How This Applies to Real Manufacturing

This approach can be directly implemented in:

* Ceramic manufacturing
* Chemical processes
* Metal and materials production
* Any process with:

  * Measurable variables
  * Quality outcomes

---

## 🧰 Tech Stack

* Python (pandas, numpy, scikit-learn)
* Data visualization (matplotlib, seaborn)
* Statistical analysis (SPC methods)

---

## 📂 Project Structure

```
01-reduce-defects-spc/
│
├── data/
├── notebooks/
│   ├── 01_exploratory_analysis.ipynb
│   ├── 02_statistical_process_control.ipynb
│   └── 03_defect_prediction_model.ipynb
│
├── src/
│   └── spc_utils.py
│
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

Run notebooks in order:

1. Exploratory analysis
2. SPC analysis
3. Modeling

---

## 📬 About Me

I am a **Process Engineer & Data Scientist** with 10+ years of experience in industrial environments (ceramics, materials, manufacturing).

I specialize in:

* Process optimization
* Defect reduction
* Statistical control (SPC / Six Sigma)
* Machine learning applied to production systems

---

## 🤝 Let’s Work Together

If your plant is facing:

* High defect rates
* Process variability
* Lack of data-driven decisions

I can help you:

✔ Identify root causes
✔ Stabilize your process
✔ Reduce scrap and improve yield

📩 Contact:

* LinkedIn
* Email

---

