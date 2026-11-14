# Machine Learning–Guided Dual-Property Prediction of Donor–π–Acceptor Nonlinear Optical Molecules

## 1. Project Overview

This repository provides the computational resources associated with the research study entitled **"Machine Learning–Guided Prediction of First Hyperpolarizability, Virtual Screening, and DFT Validation of Donor–π–Acceptor Nonlinear Optical Molecules."**

The study presents an integrated machine learning and density functional theory (DFT) framework for the simultaneous prediction of two important molecular properties:

- Maximum absorption wavelength (λmax)
- Total first-order hyperpolarizability (βtot)

Five regression algorithms were investigated to establish predictive models using a dataset of 184 donor–π–acceptor (D–π–A) chromophores. The developed models were evaluated to identify the most suitable prediction algorithm. Ridge regression demonstrated strong predictive performance for both target properties.

The established models were subsequently employed for virtual screening of new molecular candidates. Eight promising chromophores were selected for further investigation and prospective DFT validation. SHAP analysis was also performed to interpret the contributions of molecular descriptors to the predicted properties.

## 2. Repository Contents

The repository contains the following computational resources:

### A. Machine Learning Model
- Jupyter Notebook (`.ipynb`) containing the machine learning workflow.
- Data preprocessing and molecular descriptor handling.
- Training and evaluation of five regression algorithms.
- Model performance evaluation and prediction procedures.
- Virtual screening of new molecular candidates.

### B. Supporting Information
- Supporting Information Excel workbook containing the organized supplementary datasets and results.
- Molecular descriptor information.
- Selected model performance metrics.
- Predicted and screened molecular candidates.
- SHAP-based descriptor importance results.

### C. Figures
- Research figures and graphical representations associated with the machine learning models, molecular screening, and SHAP interpretation.

### D. DFT Validation
- Gaussian output files (`.log`) containing computational results.
- Formatted checkpoint files (`.fchk`) for further electronic-structure analysis, where available.

## 3. Computational Workflow

The overall computational workflow consists of the following stages:

1. Collection and preparation of the D–π–A chromophore dataset.
2. Molecular representation and descriptor generation.
3. Data preprocessing and feature selection.
4. Development and evaluation of five machine learning regression algorithms.
5. Prediction of λmax and βtot.
6. Virtual screening of new molecular candidates.
7. SHAP-based interpretation of molecular descriptors.
8. DFT validation of eight selected chromophores.

## 4. How to Access the Jupyter Notebook

The complete machine learning implementation is provided in the Jupyter Notebook available in this repository.

To access the notebook:

1. Open the repository on GitHub.
2. Navigate to the machine learning model folder.
3. Select the `.ipynb` file.
4. Open it directly on GitHub to inspect the code, or download it to execute the computational workflow.

## 5. Software and Computational Tools

The computational workflow utilizes the following tools:

- Python
- Jupyter Notebook
- RDKit (molecular descriptor calculation, where applicable)
- Scikit-learn (machine learning algorithms)
- SHAP (model interpretation)
- Gaussian (DFT calculations)
- Multiwfn (electronic-structure analysis, where applicable)

Specific computational settings and software details are provided in the corresponding notebook and Gaussian input files.

## 6. DFT Computational Files

Gaussian output files associated with the eight selected molecules are provided in the DFT validation section.

These files are included to facilitate inspection of the computational inputs and calculated electronic-structure properties.

- `.log`: Gaussian calculation output files.
- `.fchk`: Formatted checkpoint files for additional wavefunction analysis.

## 7. Data Availability

The datasets, molecular descriptors, machine learning implementation, prediction results, SHAP analysis, and available DFT computational files are provided in this repository to support research transparency and reproducibility.

**GitHub Repository:**  
https://github.com/aniqagohar62-prog/Dual-prediction-property

Research Project:** Dual-Property Prediction of D–π–A Nonlinear Optical Chromophores

**Repository:** Dual-prediction-property

**Purpose:** Research transparency, computational reproducibility, and further exploration of machine learning-guided molecular design.
