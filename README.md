# 🧠 Interpretable MRI-Based Biomarkers for Alzheimer’s Disease Classification

## 📌 Overview

This repository accompanies the research work titled **"Interpretable MRI-Based Biomarkers for Alzheimer’s Disease Classification"**.
The project focuses on developing explainable machine learning approach to identify biomarkers from longitudinal MRI data for early detection and classification of Alzheimer's Disease (AD).

Our goal is to bridge the gap between high-performing AI models and clinical interpretability by providing transparent and reproducible workflows.

---

## 🎯 Objectives

* Develop robust models for Alzheimer's Disease classification using MRI data
* Extract **interpretable biomarkers** from neuroimaging data
* Provide **reproducible pipelines** for research and clinical applications

---

## 🧬 Dataset

* Modality: Structural MRI
* Type: Cross-sectional data
* Preprocessing includes:

  * Skull stripping
  * Normalization
  * Registration
  * ROI extraction

> ⚠️ Note: Due to data privacy restrictions, the dataset is not included. Instructions for accessing publicly available datasets (e.g., ADNI) are provided below.

---

## 🧠 Methodology Overview

<p align="center">
  <img src="assets/diagram.png" alt="Pipeline Diagram" width="800"/>
</p>
## 1. Preprocessing Pipeline

* MRI standardization and alignment
* Noise reduction and intensity normalization
* Region-of-interest (ROI) extraction

### 2. Feature Extraction

* Structural biomarkers from MRI scans
* Temporal features from longitudinal data

### 3. Model Development

* Machine Learning models (e.g., Random Forest, SVM)
* Deep Learning architectures (CNN-based models)

### 4. Interpretability

* Feature importance analysis
* Model explanation techniques (e.g., SHAP, Grad-CAM)
* Identification of clinically relevant biomarkers

---

## 📊 Results

* High classification performance across AD, MCI, and CN groups
* Improved interpretability compared to black-box models
* Identification of key brain regions associated with disease progression

> Detailed metrics (Accuracy, AUC, F1-score) are available in the paper.

---

## 🛠️ Repository Structure

```
├── data/                # Data handling scripts (no raw data included)
├── preprocessing/       # MRI preprocessing pipelines
├── models/              # ML/DL model implementations
├── interpretability/    # Explainability methods (SHAP, Grad-CAM)
├── results/             # Outputs, figures, and evaluation metrics
├── notebooks/           # Jupyter notebooks for experiments
├── knime_workflows/     # KNIME pipelines (if applicable)
└── README.md
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

pip install -r requirements.txt
```

---

## ▶️ Usage

### Run preprocessing

```bash
python preprocessing/run_pipeline.py
```

### Train model

```bash
python models/train.py
```

### Generate explanations

```bash
python interpretability/explain.py
```

---

## 🔍 Reproducibility

* Fixed random seeds for experiments
* Clear pipeline separation (preprocessing → training → evaluation)
* Modular design for easy experimentation

---

## 📄 Publication

**Title:** Interpretable MRI-Based Biomarkers for Alzheimer’s Disease Classification
**Authors:** [Your Name et al.]
**Conference/Journal:** [Add here]
**Year:** [Add here]

📎 [Link to paper]

---

## 🤝 Contributions

Contributions are welcome! Please open an issue or submit a pull request for improvements or discussions.

---

## 📜 License

[Choose a license, e.g., MIT License]

---

## 📬 Contact

* Name: [Your Name]
* Email: [Your Email]
* LinkedIn: [Your Profile]

---

## ⭐ Acknowledgements

* KNIME (for workflow support and co-funded research)
* Open datasets and research community contributions
