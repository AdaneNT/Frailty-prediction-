# Predictive Modeling of Frailty Conditions in the Elderly

This repository contains Python code and Jupyter notebooks used in the experiments of  the JMIR 2020 paper:

**"Predictive Modeling for Frailty Conditions in Elderly People: Machine Learning Approaches"**  
Adane Tarekegn, Fulvio Ricceri, Giuseppe Costa, Elisa Ferracin, Mario Giacobini  
*JMIR Medical Informatics*, 2020. [DOI: 10.2196/16678](https://doi.org/10.2196/16678)

---
## Requirements

Install with pip:

```bash
pip install scikit-learn pandas numpy matplotlib seaborn jupyter
```


## What’s Included

The notebooks apply machine learning models (SVM, MLP, RF) with:
- 10-fold cross-validation
- Grid search hyperparameter tuning
- Feature selection (e.g., chi-square tests)
- Separate binary classification models for:
  - Mortality
  - Disability
  - Fracture
  - Urgent hospitalization
  - Preventable hospitalization
  - ED admission with red code

## Structure

- `notebooks/`: Jupyter notebooks for each outcome and ML model
- `requirements.txt`: Python dependencies
- `paper/`: Original research paper (PDF)

## Setup

```bash
git clone https://github.com/your-username/ML-Frailty-Prediction.git
cd ML-Frailty-Prediction
pip install -r requirements.txt
