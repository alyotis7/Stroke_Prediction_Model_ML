# Stroke_Prediction_Model_ML
The World Health Organization identifies stroke as the second leading cause of death worldwide, accounting for roughly 11% of all global deaths. This dataset aims to predict a patient's likelihood of experiencing a stroke by analyzing key input parameters such as gender, age, pre-existing medical conditions, and smoking status.
The model will be a supervised classification model. Since we have access to the ground truth labels, the model is trained on known outcomes and its performance is evaluated against them. The task is to predict whether a patient had a stroke 1 or did not 0.
```
## Project Structure

├── EDA_Stroke.ipynb   # EDA Notebook
├── Feature_Selection.ipynb # Feature selection notebook
├── Machine_Learning_Stroke.ipynb # Machine Learning notebook
├── requirements.txt          # Required Python packages
└── README.md                 # This file
```
## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/alyotis7/Stroke_Prediction_Model_ML/
cd Stroke_Prediction_Model_ML
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Download the dataset
Download the dataset directly from this repository and place the file `stroke-data.csv` in the root folder

### 4. Run the notebook
```bash
jupyter notebook EDA_Stroke.ipynb 
jupyter notebook Feature_Selection.ipynb
jupyter notebook Machine_Learning_Stroke.ipynb
```

## Models Evaluated

Logistic Regression
Random Forest
MLP

---

## Key findings
- Logistic Regression outperformed more complex models on this small imbalanced dataset
- Recall was prioritised as the primary metric missing a stroke patient carries greater risk than a false alarm
---
## Limitations
This dataset contains only 5,110 records with 4.9% stroke cases. 
Results should not be used for real clinical applications.

## Requirements
- Python 3.8+
- See `requirements.txt` for full package list
