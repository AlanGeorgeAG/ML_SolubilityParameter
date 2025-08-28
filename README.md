# **ML_SolubilityParameter**

This repository contains all ML models provided in the paper along with the dataset as a CSV file.

---

## 📊 **Dataset**

- **File:** `SM+PD2.csv`  
- **Description:**  
  This dataset is the primary input used for all models.  
  It contains molecular descriptors and properties required for building predictive models of solubility parameters.

---

## ⚙️ **Model Reduction & Feature Engineering**

Each notebook represents a combination of a prediction model with a feature engineering / dimensionality reduction technique.  
**Naming Convention:**  
`<Model>_<Technique>.ipynb`  

- **Models:** `SVR`, `RF`, `GPR`, `LASSO`, `NN`  
- **Techniques:** `PCA`, `PCC`, `RFE`, `RFECV`

---

## 🔑 **Models and Techniques**

### 1. **Support Vector Regression (SVR)**
- `SVR_PCA.ipynb` → SVR + Principal Component Analysis (PCA)  
- `SVR_PCC.ipynb` → SVR + Pearson Correlation Coefficient (PCC)  
- `SVR_RFE.ipynb` → SVR + Recursive Feature Elimination (RFE)  

### 2. **Random Forest (RF)**
- `RF_PCA.ipynb` → Random Forest + PCA  
- `RF_PCC.ipynb` → Random Forest + PCC  
- `RF_RFECV.ipynb` → Random Forest + Recursive Feature Elimination with cross-validation (RFECV)  

### 3. **Gaussian Process Regression (GPR)**
- `GPR_PCA.ipynb` → GPR + PCA  
- `GPR_PCC.ipynb` → GPR + PCC  
- `GPR_RFECV.ipynb` → GPR + RFECV  

### 4. **LASSO Regression**
- `LASSO_PCA.ipynb` → LASSO + PCA  
- `LASSO_PCC.ipynb` → LASSO + PCC  
- `LASSO_RFECV.ipynb` → LASSO + RFECV  

### 5. **Neural Networks (NN)**
- `NN_PCA.ipynb` → Neural Network + PCA  
- `NN_PCC.ipynb` → Neural Network + PCC  
- `NN_RFECV.ipynb` → Neural Network + RFECV  

---

## 📘 **How to Use**

1. Load the dataset (`SM+PD2.csv`).  
2. Open the notebook corresponding to the desired **model + feature reduction technique**.  
3. Run the notebook to reproduce results and evaluate performance.  

---

## 📑 **Notes**

### **Feature Engineering**
- **PCA**: Reduces dimensionality by transforming correlated variables into uncorrelated components.  
- **PCC**: Selects features based on their correlation with the target variable.  
- **RFECV**: Iteratively removes features and selects the optimal subset using cross-validation.  

### **Models**
- **SVR** = Support Vector Regression  
- **RF** = Random Forest  
- **GPR** = Gaussian Process Regression  
- **LASSO** =  Least Absolute Shrinkage and Selection Operator.
- **NN** = Feedforward Neural Network  

---

## 👤 **Author**

**AlanGeorgeAG**  
_All models and dataset are provided for research and reproducibility._

## 🔗 **Code & Dataset DOI**

The code and dataset are openly available through Zenodo: [![DOI](https://zenodo.org/badge/1046146756.svg)](https://doi.org/10.5281/zenodo.16980575)
